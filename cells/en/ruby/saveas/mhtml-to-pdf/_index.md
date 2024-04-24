---
title: Save MHTML as PDF using Ruby 
description: Utilizing Aspose.Cells Cloud SDK for Ruby to save MHTML format file as PDF format file. 
kwords: Excel, Save MHTML as PDF, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save MHTML as PDF using the Cells Cloud Ruby library.","description": "How to save MHTML as PDF using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/mhtml-to-pdf/","step": [{ "@type": "HowToStep","name": "How to save MHTML as PDF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/mhtml-to-pdf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save MHTML as PDF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/mhtml-to-pdf/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save MHTML as PDF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/mhtml-to-pdf/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save MHTML as PDF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/mhtml-to-pdf/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Save MHTML as PDF" h2="Ruby library for saving MHTML as PDF" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Ruby. This is a professional solution to save MHTML as PDF and other document formats online using Ruby." urlsection="saveas/mhtml-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a MHTML file as PDF in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from MHTML as PDF is a complex task. All MHTML to PDF format transitions is performed by our Ruby SDK while maintaining the source MHTML spreadsheet's main structural and logical content. Our Ruby library is a professional solution to save MHTML as PDF files online. This Cloud SDK gives Ruby developers powerful functionality and perfect PDF output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Example for saving MHTML as PDF using REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.mhtml'
    save_options = nil
    newfilename = 'Book1Saveas.pdf'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to save MHTML as PDF using the Cells Cloud Ruby library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Ruby library and add the reference (import the library) to your project.</li>
<li>Open the source file in Ruby.</li>
<li>Use the `post_workbook_save_as` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
