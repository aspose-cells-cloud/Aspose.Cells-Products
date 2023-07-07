---
title:  Exportieren Sie die Arbeitsmappe aus der Tabellenkalkulation in GIF mit PHP API
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
url: /de/php/export/workbook-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API zum Exportieren der Arbeitsmappe in eine GIF-Datei" h2="PHP-Bibliothek zum Exportieren von WORKBOOK in eine GIF-Datei" p="Verwenden Sie Cells Export REST API, um Arbeitsabläufe interner Tabellenkalkulationsobjekte in PHP zu exportieren. Dies ist eine professionelle Lösung zum Exportieren von ARBEITSBUCH in eine GIF-Formatdatei aus einer Tabellenkalkulation online mit PHP." urlsection="export/workbook-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportieren Sie das WORKBOOK-Objekt in die GIF-Formatdatei PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines WORKBOOK-Objekts aus einer Tabellenkalkulation in eine GIF-Datei ist eine komplexe Aufgabe. Übergänge im Export von WORKBOOK in das GIF-Format werden von unserem PHP SDK durchgeführt, während der Hauptstruktur- und logische Inhalt der Quell-WORKBOOK-Tabelle erhalten bleibt. Unsere PHP-Bibliothek ist eine professionelle Lösung zum Online-Export von WORKBOOK-Objekten in Dateien im GIF-Format. Dieses Cloud SDK bietet PHP Entwicklern leistungsstarke Funktionalität und eine perfekte GIF-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in PHP mit REST API zum Exportieren von WORKBOOK aus der Tabellenkalkulation in das GIF-Format" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\LightCellsApi;
    $cells = new LightCellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $files = array (
        'DataSource' =>  "C:/datasource.xlsx",
        'AssemblyTest' => "C:/assemblytest.xlsx"
    );
    $result = $cells->postExport( $files,'workbook', 'gif' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie PHP API, um WORKBOOK in GIF zu exportieren" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und Version API</li>
<li>Rufen Sie die Methode postExport auf, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>PHP 7.4 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
