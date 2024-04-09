---
title:  Exportieren Sie WORKBOOK nach SQL von Excel mit Cells Cloud SDK für PHP
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie WORKBOOK nach SQL von Excel" h2="PHP Bibliothek zum Exportieren von WORKBOOK in eine SQL-Datei" p="Verwenden Sie Export API von Cells Cloud, um Excel Datei-interne Objekt-Workflows in PHP zu exportieren. Dies ist eine professionelle Lösung, um WORKBOOK online aus einer Tabellenkalkulation in eine SQL-Formatdatei mit PHP zu exportieren." urlsection="export/workbook-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das WORKBOOK-Objekt in eine SQL-Formatdatei mit dem Cloud SDK Cells für PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines WORKBOOK-Objekts aus der Datei Excel in eine SQL-Datei ist eine komplexe Aufgabe. Übergänge im Export von WORKBOOK in das SQL-Format werden von unserem PHP SDK durchgeführt, während der strukturelle und logische Hauptinhalt der Quell-WORKBOOK-Tabelle erhalten bleibt. Unsere Bibliothek PHP ist eine professionelle Lösung zum Online-Export von WORKBOOK-Objekten in Dateien im SQL-Format. Dieses Cloud SDK bietet PHP Entwicklern leistungsstarke Funktionalität und perfekte SQL-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in PHP mit REST API zum Exportieren von WORKBOOK aus einer Tabellenkalkulation in das SQL-Format" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'workbook', 'sql' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für PHP, um Objekte aus Excel WORKBOOK nach SQL zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `postExport`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>PHP 7.4 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
