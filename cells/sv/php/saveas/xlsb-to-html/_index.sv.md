﻿---
title:  Spara XLSB som HTML API för PHP
description:  Använd Aspose.Cells Cloud SDK för PHP för att spara fil i XLSB-format som fil i HTML-format.
url: /sv/php/saveas/xlsb-to-html/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API för att spara XLSB som HTML" h2="PHP bibliotek för att spara XLSB som HTML" p="Använd Cells SaveAs REST API för att skapa anpassade arbetsflöden för kalkylblad i PHP. Detta är en professionell lösning för att spara XLSB som HTML och andra dokumentformat online med PHP." urlsection="saveas/xlsb-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en XLSB-fil som HTML i PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från XLSB som HTML är en komplex uppgift. Alla formatövergångar från XLSB till HTML utförs av vår PHP SDK samtidigt som källbladets XLSB-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt PHP-bibliotek är en professionell lösning för att spara XLSB som HTML-filer online. Denna Cloud SDK ger PHP-utvecklare kraftfull funktionalitet och perfekt HTML-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i PHP med REST API för att spara XLSB som HTML-format" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlsb';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "html";
    $newfilename = "Book1Saveas.html";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder PHP API för att spara XLSB som HTML" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop cellsSaveAsPostDocumentSaveAs-metoden för att hämta den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>PHP 7.4 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}