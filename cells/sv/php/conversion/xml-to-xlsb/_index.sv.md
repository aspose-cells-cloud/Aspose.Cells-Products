---
title:  Konvertera XML till XLSB med PHP
description:  Använda Aspose.Cells Cloud SDK för PHP för att konvertera en XML-formatfil till en XLSB-formatfil.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertera XML till XLSB" h2="PHP bibliotek för att konvertera XML till XLSB" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i PHP projekt. Detta är en professionell lösning för att konvertera XML till XLSB och andra dokumentformat online med PHP." urlsection="conversion/xml-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera XML till XLSB med Cells Cloud SDK för PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XML till XLSB kan vara en komplex uppgift. Vår PHP SDK hanterar alla XML- till XLSB-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i XML-källarket bevaras. Vårt PHP-bibliotek tillhandahåller en professionell lösning för att konvertera XML- till XLSB-filer online. Denna Cloud SDK ger PHP utvecklare kraftfull funktionalitet och säkerställer XLSB-utdata av hög kvalitet.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP Kodexempel för konvertering av XML till XLSB med Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xml';    
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
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för PHP för att konvertera Excel filer till andra format XML till XLSB" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>PHP 7.4 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
