﻿---
title:  Spara XLSM som XLS API för PHP
description:  Använder Aspose.Cells Cloud SDK för PHP för att spara XLSM-formatfil som XLS-formatfil.
url: /sv/php/saveas/xlsm-to-xls/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API för att spara XLSM som XLS" h2="PHP bibliotek för att spara XLSM som XLS" p="Använd Cells SaveAs REST API för att skapa anpassade arbetsflöden för kalkylblad i PHP. Detta är en professionell lösning för att spara XLSM som XLS och andra dokumentformat online med PHP." urlsection="saveas/xlsm-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en XLSM-fil som XLS i PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från XLSM som XLS är en komplex uppgift. Alla XLSM- till XLS-formatövergångar utförs av vår PHP SDK samtidigt som källkodens XLSM-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt PHP-bibliotek är en professionell lösning för att spara XLSM som XLS-filer online. Denna Cloud SDK ger PHP utvecklare kraftfull funktionalitet och perfekt XLS-utgång.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i PHP med REST API för att spara XLSM som XLS-format" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlsm';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "xls";
    $newfilename = "Book1Saveas.xls";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder PHP API för att spara XLSM som XLS" >}}
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