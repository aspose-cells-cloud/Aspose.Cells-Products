---
title:  Konvertera PNG till SXC med PHP
description:  Använder Aspose.Cells Cloud SDK för PHP för att konvertera en fil i PNG-format till en fil i SXC-format.
kwords: Excel, Convert PNG to SXC, REST, PHP
howto: How to convert PNG to SXC using Aspose.Cells Cloud PHP library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera PNG till SXC" h2="PHP bibliotek för att konvertera PNG till SXC" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i PHP projekt. Detta är en professionell lösning för att konvertera PNG till SXC och andra dokumentformat online med PHP." urlsection="conversion/png-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera PNG till SXC med Cells Cloud SDK för PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från PNG till SXC kan vara en komplex uppgift. Vår PHP SDK hanterar alla PNG till SXC-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket PNG bevaras. Vårt PHP-bibliotek tillhandahåller en professionell lösning för att konvertera PNG till SXC-filer online. Denna Cloud SDK ger PHP utvecklare kraftfull funktionalitet och säkerställer högkvalitativa SXC-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Kod Exempel för att konvertera PNG till SXC med Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.png';    
    $format ='sxc';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.sxc", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar PNG till SXC med hjälp av Cells Cloud PHP-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera PHP-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i PHP.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>PHP 7.4 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
