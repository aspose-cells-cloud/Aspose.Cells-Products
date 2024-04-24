---
title: Convert TSV to XLS using Ruby 
description: Utilizing the Aspose.Cells Cloud SDK for Ruby to convert a TSV format file to a XLS format file. 
kwords: Excel, Convert TSV to XLS, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert TSV to XLS using the Cells Cloud Ruby library.","description": "How to convert TSV to XLS using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/conversion/tsv-to-xls/","step": [{ "@type": "HowToStep","name": "How to convert TSV to XLS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/tsv-to-xls/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert TSV to XLS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/tsv-to-xls/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert TSV to XLS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/tsv-to-xls/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to convert TSV to XLS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/tsv-to-xls/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert TSV to XLS" h2="Ruby library for converting TSV to XLS" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Ruby projects. This is a professional solution to convert TSV to XLS and other document formats online using Ruby." urlsection="conversion/tsv-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert TSV to XLS using Cells Cloud SDK for Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from TSV to XLS can be a complex task. Our Ruby SDK handles all TSV to XLS format conversions while preserving the main structural and logical content of the source TSV spreadsheet. Our Ruby library provides a professional solution for converting TSV to XLS files online. This Cloud SDK empowers Ruby developers with powerful functionality and ensures high-quality XLS output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Example for converting TSV to XLS using Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.tsv"
            format = 'xls'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to convert TSV to XLS using the Cells Cloud Ruby library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Ruby library and add the reference (import the library) to your project.</li>
<li>Open the source file in Ruby.</li>
<li>Use the `put_convert_workbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
