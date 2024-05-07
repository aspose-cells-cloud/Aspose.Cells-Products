---
title:  Konvertera MHTML till XLSB med PHP
description:  Använda Aspose.Cells Cloud SDK för PHP för att konvertera en fil i MHTML-format till en fil i XLSB-format.
kwords: Excel, Convert MHTML to XLSB, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert MHTML to XLSB using the Cells Cloud PHP library.","description": "How to convert MHTML to XLSB using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/mhtml-to-xlsb/","step": [{ "@type": "HowToStep","name": "How to convert MHTML to XLSB using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/mhtml-to-xlsb/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert MHTML to XLSB using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/mhtml-to-xlsb/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert MHTML to XLSB using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/mhtml-to-xlsb/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert MHTML to XLSB using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/mhtml-to-xlsb/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera MHTML till XLSB" h2="PHP bibliotek för att konvertera MHTML till XLSB" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i PHP projekt. Detta är en professionell lösning för att konvertera MHTML till XLSB och andra dokumentformat online med PHP." urlsection="conversion/mhtml-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera MHTML till XLSB med Cells Cloud SDK för PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från MHTML till XLSB kan vara en komplex uppgift. Vår PHP SDK hanterar alla konverteringar av MHTML till XLSB-format samtidigt som det huvudsakliga strukturella och logiska innehållet i MHTML-källarket bevaras. Vårt PHP-bibliotek tillhandahåller en professionell lösning för att konvertera MHTML till XLSB-filer online. Denna Cloud SDK ger PHP utvecklare kraftfull funktionalitet och säkerställer XLSB-utdata av hög kvalitet.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Kodexempel för att konvertera MHTML till XLSB med Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.mhtml';    
    $format ='xlsb';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xlsb", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man konverterar MHTML till XLSB med hjälp av Cells Cloud PHP-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera PHP-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i PHP.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>PHP 7.4 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
