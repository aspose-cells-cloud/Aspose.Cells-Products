﻿---
title:  Spara TXT som FODS med PHP
description:  Använder Aspose.Cells Cloud SDK för PHP för att spara TXT-formatfil som FODS-formatfil.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Spara TXT som FODS" h2="PHP bibliotek för att spara TXT som FODS" p="Använd SaveAs API av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i PHP. Detta är en professionell lösning för att spara TXT som FODS och andra dokumentformat online med PHP." urlsection="saveas/txt-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en TXT-fil som FODS i PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från TXT som FODS är en komplex uppgift. Alla TXT- till FODS-formatövergångar utförs av vår PHP SDK med bibehållande av källkodens TXT-kalkylblads huvudsakliga strukturella och logiska innehåll. Vårt PHP-bibliotek är en professionell lösning för att spara TXT som FODS-filer online. Denna Cloud SDK ger PHP utvecklare kraftfull funktionalitet och perfekt FODS-utgång.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP Kod Exempel för att spara TXT som FODS med REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.txt';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "fods";
    $newfilename = "Book1Saveas.fods";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för PHP för att spara Excel filer som andra format TXT som FODS" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `PostWorkbookSaveAs` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>PHP 7.4 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
