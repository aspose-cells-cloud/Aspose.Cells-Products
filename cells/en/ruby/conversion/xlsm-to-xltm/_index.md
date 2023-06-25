---
title: XLSM to XLTM Convert API for Ruby 
description: Using Aspose.Cells Cloud SDK for Ruby to convert XLSM format file to XLTM format file. 
url: /ruby/conversion/xlsm-to-xltm/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API to convert XLSM to XLTM" h2="Ruby library to convert XLSM to XLTM" p="Use Cells Conversion REST API to create customized spreadsheet workflows in Ruby. This is a professional solution to convert XLSM to XLTM and other document formats online using Ruby." urlsection="conversion/xlsm-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a XLSM file to XLTM in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLSM to XLTM is a complex task. All XLSM to XLTM format transitions is performed by our Ruby SDK while maintaining the source XLSM spreadsheet's main structural and logical content. Our Ruby library is a professional solution to convert XLSM to XLTM files online. This Cloud SDK gives Ruby developers powerful functionality and perfect XLTM output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Ruby using REST API to convert XLSM to XLTM format" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlsm"
            format = 'xltm'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Ruby API to convert  XLSM to XLTM" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cells_workbook_put_convert_workbook method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
