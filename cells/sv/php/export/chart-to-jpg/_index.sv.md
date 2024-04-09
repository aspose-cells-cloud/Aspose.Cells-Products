---
title: Exportera CHART till JPG från Excel med Cells Cloud SDK för PHP
description:  Aspose.Cells Cloud REST API stöder export av filer från {0} till {1}-format med {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportera CHART till JPG från Excel" h2="PHP-bibliotek för att exportera CHART till JPG-fil" p="Använd Export API av Cells Cloud för att exportera Excel fil interna objekt arbetsflöden i PHP. Detta är en professionell lösning för att exportera CHART till JPG-format fil från kalkylblad online med PHP." urlsection="export/chart-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportera CHART-objekt till JPG-formatfil med Cells Cloud SDK för PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportera CHART-objekt till JPG-fil från Excel-filen är en komplex uppgift. Exportera CHART till JPG-formatövergångar utförs av vår PHP SDK samtidigt som källdiagrammets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt PHP-bibliotek är en professionell lösning för att exportera CHART-objekt till JPG-formatfiler online. Denna Cloud SDK ger PHP utvecklare kraftfull funktionalitet och perfekt JPG-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Kodexempel i PHP med REST API för att exportera CHART till JPG-format från kalkylblad" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'chart', 'jpg' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för PHP för att exportera objekt från Excel CHART till JPG" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `postExport` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>PHP 7.4 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
