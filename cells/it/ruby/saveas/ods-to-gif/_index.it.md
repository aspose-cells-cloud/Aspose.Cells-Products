---
title:  Salva ODS come GIF utilizzando Ruby
description:  Utilizzando Aspose.Cells Cloud SDK per Ruby per salvare il file in formato ODS come file in formato GIF.
kwords: Excel, Save ODS as GIF, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save ODS as GIF using the Cells Cloud Ruby library.","description": "How to save ODS as GIF using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/ods-to-gif/","step": [{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-gif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-gif/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-gif/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-gif/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Salva ODS come GIF" h2="Libreria Ruby per salvare ODS come GIF" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati per fogli di calcolo in Ruby. Questa è una soluzione professionale per salvare ODS come GIF e altri formati di documenti online utilizzando Ruby." urlsection="saveas/ods-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Salva un file ODS come GIF in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da ODS come GIF è un compito complesso. Tutte le transizioni dal formato ODS al formato GIF vengono eseguite dal nostro SDK Ruby mantenendo il contenuto strutturale e logico principale del foglio di calcolo ODS di origine. La nostra libreria Ruby è una soluzione professionale per salvare ODS come file GIF online. Questo Cloud SDK offre agli sviluppatori Ruby funzionalità potenti e un output GIF perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice Ruby per salvare ODS come GIF utilizzando REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.ods'
    save_options = nil
    newfilename = 'Book1Saveas.gif'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come salvare ODS come GIF utilizzando la libreria Cloud Ruby Cells." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Ruby e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in Ruby.</li>
<li>Utilizza il metodo `post_workbook_save_as` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>rubino 2.5 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
