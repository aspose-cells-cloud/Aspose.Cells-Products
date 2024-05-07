---
title:  Converti i NUMERI in XPS utilizzando PHP
description:  Utilizzando Aspose.Cells Cloud SDK per PHP per convertire un file in formato NUMERI in un file in formato XPS.
kwords: Excel, Convert NUMBERS to XPS, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert NUMBERS to XPS using the Cells Cloud PHP library.","description": "How to convert NUMBERS to XPS using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/numbers-to-xps/","step": [{ "@type": "HowToStep","name": "How to convert NUMBERS to XPS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/numbers-to-xps/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert NUMBERS to XPS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/numbers-to-xps/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to XPS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/numbers-to-xps/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to XPS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/numbers-to-xps/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti i NUMERI in XPS" h2="Libreria PHP per convertire i NUMERI in XPS" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti PHP. Questa è una soluzione professionale per convertire i NUMERI in XPS e altri formati di documenti online utilizzando PHP." urlsection="conversion/numbers-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti NUMERI in XPS utilizzando Cells Cloud SDK per PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da NUMBERS a XPS può essere un compito complesso. Il nostro SDK PHP gestisce tutte le conversioni del formato NUMBERS in XPS preservando il contenuto strutturale e logico principale del foglio di calcolo NUMBERS di origine. La nostra libreria PHP fornisce una soluzione professionale per convertire online i file NUMBERS in XPS. Questo Cloud SDK offre agli sviluppatori PHP potenti funzionalità e garantisce un output XPS di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Esempio di codice per convertire i NUMERI in XPS utilizzando Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.numbers';    
    $format ='xps';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xps", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come convertire i NUMERI in XPS utilizzando la libreria Cells Cloud PHP." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria PHP e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in PHP.</li>
<li>Utilizza il metodo `putConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>PHP 7.4 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
