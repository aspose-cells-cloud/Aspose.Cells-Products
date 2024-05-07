---
title:  Salva XLSB come XLSM utilizzando Python
description:  Utilizzando Aspose.Cells Cloud SDK per Python per salvare il file in formato XLSB come file in formato XLSM.
kwords: Excel, Save XLSB as XLSM, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSB as XLSM using the Cells Cloud Python library.","description": "How to save XLSB as XLSM using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/xlsb-to-xlsm/","step": [{ "@type": "HowToStep","name": "How to save XLSB as XLSM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsb-to-xlsm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSB as XLSM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsb-to-xlsm/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSB as XLSM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsb-to-xlsm/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save XLSB as XLSM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsb-to-xlsm/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Salva XLSB come XLSM" h2="Python libreria per salvare XLSB come XLSM" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati per fogli di calcolo in Python. Si tratta di una soluzione professionale per salvare XLSB come XLSM e altri formati di documenti online utilizzando Python." urlsection="saveas/xlsb-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Salva un file XLSB come XLSM in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da XLSB come XLSM è un compito complesso. Tutte le transizioni dal formato XLSB al formato XLSM vengono eseguite dal nostro SDK Python mantenendo il contenuto strutturale e logico principale del foglio di calcolo XLSB di origine. La nostra libreria Python è una soluzione professionale per salvare online XLSB come file XLSM. Questo Cloud SDK offre agli sviluppatori Python funzionalità potenti e un output XLSM perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Codice Esempio per salvare XLSB come XLSM utilizzando REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsb'    
    saveOptions = None
    newfilename = "Book1Saveas.xlsm"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come salvare XLSB come XLSM utilizzando la libreria Cells Cloud Python." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Python e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in Python.</li>
<li>Utilizza il metodo `post_workbook_save_as` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Python 2.7 o successiva</li>
<li>Python 3.10 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
