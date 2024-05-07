---
title:  Esporta WORKBOOK in SQL da Excel utilizzando Cells Cloud SDK per PHP
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
kwords: Excel, workbook, sql, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for PHP to export objects from Excel WORKBOOK to SQL","description": "How to use Cells Cloud SDK for PHP to export objects from Excel WORKBOOK to SQL","image": {"@type": "ImageObject"},"url": "/php/export/workbook-to-sql/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel WORKBOOK to SQL step 1", "image": {"@type": "ImageObject",},"url": "/php/export/workbook-to-sql/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel WORKBOOK to SQL step 1", "image": {"@type": "ImageObject",},"url": "/php/export/workbook-to-sql/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel WORKBOOK to SQL step 1", "image": {"@type": "ImageObject",},"url": "/php/export/workbook-to-sql/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Esporta cartella di lavoro in SQL da Excel" h2="PHP libreria per esportare WORKBOOK in file SQL" p="Utilizza Esporta API di Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in PHP. Questa è una soluzione professionale per esportare la cartella di lavoro in un file in formato SQL dal foglio di calcolo online utilizzando PHP." urlsection="export/workbook-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="Esporta l\'oggetto WORKBOOK in un file in formato SQL utilizzando Cells Cloud SDK per PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto WORKBOOK in un file SQL dal file Excel è un'attività complessa. L'esportazione di WORKBOOK in transizioni in formato SQL viene eseguita dal nostro SDK PHP mantenendo il contenuto strutturale e logico principale del foglio di calcolo WORKBOOK di origine. La nostra libreria PHP è una soluzione professionale per esportare online oggetti WORKBOOK in file in formato SQL. Questo Cloud SDK offre agli sviluppatori PHP funzionalità potenti e output SQL perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice in PHP utilizzando REST API per esportare WORKBOOK in formato SQL dal foglio di calcolo" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'workbook', 'sql' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per PHP per esportare oggetti da Excel WORKBOOK a SQL" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `postExport` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>PHP 7.4 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
