﻿---
title:  Exportera LISTOBJECT till EMF från kalkylblad med PHP API
description:  Aspose.Cells Cloud REST API stöder export av filer från {0} till {1}-format med {2}.
url: /sv/php/export/listobject-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API för att exportera LISTOBJECT till EMF fil" h2="PHP bibliotek för att exportera LISTOBJECT till EMF fil" p="Använd Cells Export REST API för att exportera arbetsflöden för kalkylbladsinterna objekt i PHP. Detta är en professionell lösning för att exportera LISTOBJECT till EMF-formatfil från kalkylark online med PHP." urlsection="export/listobject-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportera LISTOBJECT-objekt till EMF filformat i PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportera LISTOBJECT-objekt till EMF-fil från kalkylblad är en komplex uppgift. Export av LISTOBJECT till EMF formatövergångar utförs av vår PHP SDK samtidigt som källbladets LISTOBJECT-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt PHP-bibliotek är en professionell lösning för att exportera LISTOBJECT-objekt till filer i EMF-format online. Denna Cloud SDK ger PHP-utvecklare kraftfull funktionalitet och perfekt EMF-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i PHP med REST API för att exportera LISTOBJECT till EMF-format från kalkylblad" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'listobject', 'emf' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder PHP API för att exportera LISTOBJECT till EMF" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop postExport-metoden för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>PHP 7.4 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}