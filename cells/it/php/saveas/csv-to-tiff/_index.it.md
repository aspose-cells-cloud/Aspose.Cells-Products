---
title:  Salva CSV come TIFF utilizzando PHP
description:  Utilizzando Aspose.Cells Cloud SDK per PHP per salvare il file in formato CSV come file in formato TIFF.
kwords: Excel, Save CSV as TIFF, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save CSV as TIFF using the Cells Cloud PHP library.","description": "How to save CSV as TIFF using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/saveas/csv-to-tiff/","step": [{ "@type": "HowToStep","name": "How to save CSV as TIFF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/csv-to-tiff/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save CSV as TIFF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/csv-to-tiff/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save CSV as TIFF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/csv-to-tiff/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to save CSV as TIFF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/csv-to-tiff/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Salva CSV come TIFF" h2="Libreria PHP per salvare CSV come TIFF" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati per fogli di calcolo in PHP. Si tratta di una soluzione professionale per salvare CSV come TIFF e altri formati di documenti online utilizzando PHP." urlsection="saveas/csv-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Salva un file CSV come TIFF in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da CSV come TIFF è un compito complesso. Tutte le transizioni dal formato CSV al formato TIFF vengono eseguite dal nostro SDK PHP mantenendo il contenuto strutturale e logico principale del foglio di calcolo CSV di origine. La nostra libreria PHP è una soluzione professionale per salvare online CSV come file TIFF. Questo Cloud SDK offre agli sviluppatori PHP funzionalità potenti e un output TIFF perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Codice Esempio per salvare CSV come TIFF utilizzando REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.csv';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "tiff";
    $newfilename = "Book1Saveas.tiff";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come salvare CSV come TIFF utilizzando la libreria Cells Cloud PHP." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria PHP e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in PHP.</li>
<li>Utilizza il metodo `PostWorkbookSaveAs` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>PHP 7.4 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
