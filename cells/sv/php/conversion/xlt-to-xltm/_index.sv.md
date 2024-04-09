---
title:  Konvertera XLT till XLTM med PHP
description:  Använda Aspose.Cells Cloud SDK för PHP för att konvertera en fil i XLT-format till en fil i XLTM-format.
kwords: Excel, Convert XLT to XLTM, REST, PHP
howto: How to convert XLT to XLTM using Aspose.Cells Cloud PHP library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera XLT till XLTM" h2="PHP bibliotek för konvertering av XLT till XLTM" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i PHP projekt. Detta är en professionell lösning för att konvertera XLT till XLTM och andra dokumentformat online med PHP." urlsection="conversion/xlt-to-xltm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera XLT till XLTM med Cells Cloud SDK för PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLT till XLTM kan vara en komplex uppgift. Vår PHP SDK hanterar alla XLT- till XLTM-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i käll-XLT-kalkylarket bevaras. Vårt PHP-bibliotek tillhandahåller en professionell lösning för att konvertera XLT- till XLTM-filer online. Denna Cloud SDK ger PHP-utvecklare kraftfull funktionalitet och säkerställer XLTM-utdata av hög kvalitet.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Kodexempel för att konvertera XLT till XLTM med Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlt';    
    $format ='xltm';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xltm", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar XLT till XLTM med hjälp av Cells Cloud PHP-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera PHP-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i PHP.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>PHP 7.4 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
