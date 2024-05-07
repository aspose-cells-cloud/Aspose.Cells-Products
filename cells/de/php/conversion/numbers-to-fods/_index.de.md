---
title:  Konvertieren Sie NUMBERS mit PHP in FODS
description:  Verwendung des Aspose.Cells Cloud SDK für PHP zum Konvertieren einer Datei im NUMBERS-Format in eine Datei im FODS-Format.
kwords: Excel, Convert NUMBERS to FODS, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert NUMBERS to FODS using the Cells Cloud PHP library.","description": "How to convert NUMBERS to FODS using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/numbers-to-fods/","step": [{ "@type": "HowToStep","name": "How to convert NUMBERS to FODS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/numbers-to-fods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert NUMBERS to FODS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/numbers-to-fods/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to FODS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/numbers-to-fods/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to FODS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/numbers-to-fods/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie NUMBERS in FODS" h2="PHP Bibliothek zur Konvertierung von NUMBERS in FODS" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in PHP-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von NUMBERS in FODS und andere Dokumentformate unter PHP." urlsection="conversion/numbers-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie NUMBERS mit dem Cloud SDK Cells für PHP in FODS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von NUMBERS in FODS kann eine komplexe Aufgabe sein. Unser PHP SDK übernimmt alle Konvertierungen des NUMBERS- in das FODS-Formats und behält dabei den wichtigsten strukturellen und logischen Inhalt der Quell-NUMBERS-Tabelle bei. Unsere PHP-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von NUMBERS- in FODS-Dateien. Dieses Cloud SDK bietet PHP-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige FODS-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Codebeispiel für die Konvertierung von NUMBERS in FODS mithilfe des Cloud SDK Cells" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.numbers';    
    $format ='fods';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.fods", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So konvertieren Sie NUMBERS mit der Cells Cloud PHP-Bibliothek in FODS." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek PHP und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in PHP.</li>
<li>Verwenden Sie die Methode `putConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>PHP 7.4 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
