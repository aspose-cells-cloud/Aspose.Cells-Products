---
title: Convert HTML to MD using Ruby 
description: Utilizing the Aspose.Cells Cloud SDK for Ruby to convert a HTML format file to a MD format file. 
kwords: Excel, Convert HTML to MD, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert HTML to MD using the Cells Cloud Ruby library.","description": "How to convert HTML to MD using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/conversion/html-to-md/","step": [{ "@type": "HowToStep","name": "How to convert HTML to MD using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/html-to-md/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert HTML to MD using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/html-to-md/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert HTML to MD using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/html-to-md/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to convert HTML to MD using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/html-to-md/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert HTML to MD" h2="Ruby library for converting HTML to MD" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Ruby projects. This is a professional solution to convert HTML to MD and other document formats online using Ruby." urlsection="conversion/html-to-md/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert HTML to MD using Cells Cloud SDK for Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from HTML to MD can be a complex task. Our Ruby SDK handles all HTML to MD format conversions while preserving the main structural and logical content of the source HTML spreadsheet. Our Ruby library provides a professional solution for converting HTML to MD files online. This Cloud SDK empowers Ruby developers with powerful functionality and ensures high-quality MD output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Example for converting HTML to MD using Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.html"
            format = 'md'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to convert HTML to MD using the Cells Cloud Ruby library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Ruby library and add the reference (import the library) to your project.</li>
<li>Open the source file in Ruby.</li>
<li>Use the `put_convert_workbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
