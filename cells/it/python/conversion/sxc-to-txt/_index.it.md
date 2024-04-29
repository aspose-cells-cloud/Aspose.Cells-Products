---
title:  Converti SXC in TXT utilizzando Python
description:  Utilizzando Aspose.Cells Cloud SDK per Python per convertire un file in formato SXC in un file in formato TXT.
kwords: Excel, Convert SXC to TXT, REST, Python
howto: "{"@context": "https://schema.org","@type": "HowTo","name": "How to convert SXC to TXT using the Cells Cloud Python library.","description": "How to convert SXC to TXT using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/conversion/sxc-to-txt/","step": [{ "@type": "HowToStep","name": "How to convert SXC to TXT using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/sxc-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert SXC to TXT using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/sxc-to-txt/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert SXC to TXT using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/sxc-to-txt/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to convert SXC to TXT using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/sxc-to-txt/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}"
fqa: "{"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}"
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti SXC in TXT" h2="Python libreria per convertire SXC in TXT" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Python. Questa è una soluzione professionale per convertire SXC in TXT e altri formati di documenti online utilizzando Python." urlsection="conversion/sxc-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti SXC in TXT utilizzando Cells Cloud SDK per Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da SXC a TXT può essere un compito complesso. Il nostro SDK Python gestisce tutte le conversioni dal formato SXC a TXT preservando il contenuto strutturale e logico principale del foglio di calcolo SXC di origine. La nostra libreria Python fornisce una soluzione professionale per convertire file SXC in TXT online. Questo Cloud SDK offre agli sviluppatori Python potenti funzionalità e garantisce un output TXT di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Esempio di codice per convertire SXC in TXT utilizzando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.sxc",format="txt")
    shutil.move(file1, "destFile.txt")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come convertire SXC in TXT utilizzando la libreria Cells Cloud Python." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Python e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in Python.</li>
<li>Utilizza il metodo `put_convert_workbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Python 2.7 o successiva</li>
<li>Python 3.10 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
