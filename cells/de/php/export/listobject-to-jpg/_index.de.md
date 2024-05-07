---
title:  Exportieren Sie LISTOBJECT von Excel in JPG mit Cells Cloud SDK für PHP
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords: Excel, listobject, jpg, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to JPG","description": "How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to JPG","image": {"@type": "ImageObject"},"url": "/php/export/listobject-to-jpg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to JPG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/listobject-to-jpg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to JPG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/listobject-to-jpg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to JPG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/listobject-to-jpg/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie LISTOBJECT von Excel in JPG" h2="PHP-Bibliothek zum Exportieren von LISTOBJECT in eine JPG-Datei" p="Verwenden Sie Export API von Cells Cloud, um Excel dateiinterne Objektworkflows in PHP zu exportieren. Dies ist eine professionelle Lösung, um LISTOBJECT online aus einer Tabellenkalkulation in eine JPG-Formatdatei mit PHP zu exportieren." urlsection="export/listobject-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das LISTOBJECT-Objekt in eine Datei im JPG-Format mit dem Cloud SDK Cells für PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines LISTOBJECT-Objekts aus der Datei Excel in eine JPG-Datei ist eine komplexe Aufgabe. Der Export von LISTOBJECT-Formatübergängen in das JPG-Format wird von unserem SDK PHP durchgeführt, während der strukturelle und logische Hauptinhalt der Quell-LISTOBJECT-Tabelle erhalten bleibt. Unsere PHP-Bibliothek ist eine professionelle Lösung zum Online-Export von LISTOBJECT-Objekten in JPG-Formatdateien. Dieses Cloud SDK bietet PHP Entwicklern leistungsstarke Funktionalität und perfekte JPG-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in PHP mit REST API zum Exportieren von LISTOBJECT in das JPG-Format aus einer Tabellenkalkulation" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'listobject', 'jpg' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie das Cells Cloud SDK für PHP, um Objekte aus Excel LISTOBJECT in JPG zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `postExport`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>PHP 7.4 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
