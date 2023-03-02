---
title:  Exportieren Sie PICTURE in JPG aus der Tabelle mit PHP API
description: Aspose.Cells Cloud REST API unterstützt den Export von Excel Dateien und internen Objekten in Formatdateien. SDK unterstützt Arten von Entwicklungssprachen. Dazu gehören Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby und Swift.
url: /de/php/export/picture-to-jpg/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API zum Exportieren von BILD in eine JPG-Datei" h2="PHP Bibliothek zum Exportieren von BILD in eine JPG-Datei" p="Verwenden Sie Cells Export REST API, um interne Objekt-Workflows von Tabellenkalkulationen in PHP zu exportieren. Dies ist eine professionelle Lösung zum Exportieren von PICTURE-Dateien in das JPG-Format aus Tabellenkalkulationen online mit PHP." urlsection="export/picture-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportieren Sie das PICTURE-Objekt in eine Datei im JPG-Format in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren von PICTURE-Objekten in eine JPG-Datei aus einer Tabelle ist eine komplexe Aufgabe. Der Export von BILD zu JPG-Formatübergängen wird von unserem PHP SDK durchgeführt, während der strukturelle und logische Hauptinhalt der BILD-Quelltabelle beibehalten wird. Unsere PHP-Bibliothek ist eine professionelle Lösung, um PICTURE-Objekte online in Dateien im JPG-Format zu exportieren. Dieses Cloud-SDK bietet PHP-Entwicklern leistungsstarke Funktionen und eine perfekte JPG-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in PHP mit REST API zum Exportieren von PICTURE in das JPG-Format aus der Tabelle" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'picture', 'jpg' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie PHP API, um BILD in JPG zu exportieren" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und API-Version</li>
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
