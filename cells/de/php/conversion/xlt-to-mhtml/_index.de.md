---
title:  Konvertieren Sie XLT mit PHP in MHTML
description:  Verwendung des Aspose.Cells Cloud SDK für PHP zum Konvertieren einer XLT-Formatdatei in eine MHTML-Formatdatei.
kwords: Excel, Convert XLT to MHTML, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLT to MHTML using the Cells Cloud PHP library.","description": "How to convert XLT to MHTML using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/xlt-to-mhtml/","step": [{ "@type": "HowToStep","name": "How to convert XLT to MHTML using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlt-to-mhtml/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLT to MHTML using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlt-to-mhtml/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLT to MHTML using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlt-to-mhtml/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert XLT to MHTML using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlt-to-mhtml/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie XLT in MHTML" h2="PHP Bibliothek zum Konvertieren von XLT in MHTML" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in PHP-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLT in MHTML und andere Dokumentformate unter PHP." urlsection="conversion/xlt-to-mhtml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie XLT in MHTML mit dem Cloud SDK Cells für PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLT in MHTML kann eine komplexe Aufgabe sein. Unser PHP SDK übernimmt alle Konvertierungen des XLT- in das MHTML-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLT-Quelltabelle bei. Unsere PHP-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLT- in MHTML-Dateien. Dieses Cloud SDK bietet PHP-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige MHTML-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Codebeispiel für die Konvertierung von XLT in MHTML mit Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlt';    
    $format ='mhtml';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.mhtml", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So konvertieren Sie XLT mit der Cells Cloud PHP-Bibliothek in MHTML." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek PHP und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in PHP.</li>
<li>Verwenden Sie die Methode `putConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>PHP 7.4 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
