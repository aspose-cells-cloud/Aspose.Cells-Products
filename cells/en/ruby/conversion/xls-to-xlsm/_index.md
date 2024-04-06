---
title: Convert XLS to XLSM using Ruby 
description: Utilizing the Aspose.Cells Cloud SDK for Ruby to convert a XLS format file to a XLSM format file. 
kwords: Excel, Convert XLS to XLSM, REST, Ruby
howto: How to convert XLS to XLSM using Aspose.Cells Cloud Ruby library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert XLS to XLSM" h2="Ruby library for converting XLS to XLSM" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Ruby projects. This is a professional solution to convert XLS to XLSM and other document formats online using Ruby." urlsection="conversion/xls-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert XLS to XLSM using Cells Cloud SDK for Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLS to XLSM can be a complex task. Our Ruby SDK handles all XLS to XLSM format conversions while preserving the main structural and logical content of the source XLS spreadsheet. Our Ruby library provides a professional solution for converting XLS to XLSM files online. This Cloud SDK empowers Ruby developers with powerful functionality and ensures high-quality XLSM output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Example for converting XLS to XLSM using Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xls"
            format = 'xlsm'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to convert XLS to XLSM using the Cells Cloud Ruby library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Ruby library and add the reference (import the library) to your project.</li>
<li>Open the source file in Ruby.</li>
<li>Use the `put_convert_workbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
