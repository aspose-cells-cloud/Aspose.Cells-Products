---
title:  Exportieren Sie PICTURE von Excel nach SVG mit dem Cloud SDK Cells für PHP
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords: Excel, picture, svg, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for PHP to export objects from Excel PICTURE to SVG","description": "How to use Cells Cloud SDK for PHP to export objects from Excel PICTURE to SVG","image": {"@type": "ImageObject"},"url": "/php/export/picture-to-svg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel PICTURE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/picture-to-svg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel PICTURE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/picture-to-svg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel PICTURE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/picture-to-svg/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie BILD von Excel nach SVG" h2="PHP-Bibliothek zum Exportieren von PICTURE in die Datei SVG" p="Verwenden Sie Export API von Cells Cloud, um Excel Datei-interne Objekt-Workflows in PHP zu exportieren. Dies ist eine professionelle Lösung, um PICTURE online mit PHP aus einer Tabellenkalkulation in das Format SVG zu exportieren." urlsection="export/picture-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das PICTURE-Objekt in die Formatdatei SVG mit dem Cloud SDK Cells für PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren des PICTURE-Objekts aus der Datei Excel in die Datei SVG ist eine komplexe Aufgabe. Der Export von PICTURE-Formatübergängen in das SVG-Format wird von unserem PHP-SDK durchgeführt, während der strukturelle und logische Hauptinhalt der PICTURE-Quelltabelle erhalten bleibt. Unsere PHP-Bibliothek ist eine professionelle Lösung, um PICTURE-Objekte online in Dateien im Format SVG zu exportieren. Dieses Cloud SDK bietet PHP Entwicklern leistungsstarke Funktionalität und eine perfekte SVG Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in PHP mit REST API zum Exportieren von PICTURE in das Format SVG aus der Tabellenkalkulation" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'picture', 'svg' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für PHP, um Objekte von Excel PICTURE nach SVG zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `postExport`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>PHP 7.4 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
