---
title: Convert FODS to XLTX using Ruby 
description: Utilizing the Aspose.Cells Cloud SDK for Ruby to convert a FODS format file to a XLTX format file. 
kwords: Excel, Convert FODS to XLTX, REST, Ruby
howto: How to convert FODS to XLTX using Aspose.Cells Cloud Ruby library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert FODS to XLTX" h2="Ruby library for converting FODS to XLTX" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Ruby projects. This is a professional solution to convert FODS to XLTX and other document formats online using Ruby." urlsection="conversion/fods-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert FODS to XLTX using Cells Cloud SDK for Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from FODS to XLTX can be a complex task. Our Ruby SDK handles all FODS to XLTX format conversions while preserving the main structural and logical content of the source FODS spreadsheet. Our Ruby library provides a professional solution for converting FODS to XLTX files online. This Cloud SDK empowers Ruby developers with powerful functionality and ensures high-quality XLTX output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Example for converting FODS to XLTX using Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.fods"
            format = 'xltx'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to convert FODS to XLTX using the Cells Cloud Ruby library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Ruby library and add the reference (import the library) to your project.</li>
<li>Open the source file in Ruby.</li>
<li>Use the `put_convert_workbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
