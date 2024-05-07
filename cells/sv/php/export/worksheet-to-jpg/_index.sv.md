---
title:  Exportera ARBETSBLAD till JPG från Excel med Cells Cloud SDK för PHP
description:  Aspose.Cells Cloud REST API stöder export av filer från {0} till {1}-format med {2}.
kwords: Excel, worksheet, jpg, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for PHP to export objects from Excel WORKSHEET to JPG","description": "How to use Cells Cloud SDK for PHP to export objects from Excel WORKSHEET to JPG","image": {"@type": "ImageObject"},"url": "/php/export/worksheet-to-jpg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel WORKSHEET to JPG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/worksheet-to-jpg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel WORKSHEET to JPG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/worksheet-to-jpg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel WORKSHEET to JPG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/worksheet-to-jpg/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportera ARBETSBLAD till JPG från Excel" h2="PHP-bibliotek för att exportera ARBETSBLAD till JPG-fil" p="Använd Export API av Cells Cloud för att exportera Excel fil interna objekt arbetsflöden i PHP. Detta är en professionell lösning för att exportera ARBETSBLAD till JPG-format fil från kalkylblad online med PHP." urlsection="export/worksheet-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportera WORKSHEET-objekt till JPG-formatfil med Cells Cloud SDK för PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportera WORKSHEET-objekt till JPG-fil från Excel-filen är en komplex uppgift. Exportera ARBETSBLAD till JPG-formatövergångar utförs av vår PHP SDK samtidigt som källarbetsbladets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt PHP-bibliotek är en professionell lösning för att exportera WORKSHEET-objekt till JPG-formatfiler online. Denna Cloud SDK ger PHP utvecklare kraftfull funktionalitet och perfekt JPG-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Kodexempel i PHP med REST API för att exportera WORKSHEET till JPG-format från kalkylark" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'worksheet', 'jpg' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för PHP för att exportera objekt från Excel WORKSHEET till JPG" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `postExport` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>PHP 7.4 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
