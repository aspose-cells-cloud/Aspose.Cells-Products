---
title: Export WORKBOOK to WMF from spreadsheet using Ruby  API 
description: Aspose.Cells Cloud REST API support exporting Excel file and internal objects to kinds of format files. SDK support kinds of development languages. They include Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby, and swift. 
url: /ruby/export/workbook-to-wmf/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API to export WORKBOOK to WMF file" h2="Ruby library to export WORKBOOK to WMF file" p="Use Cells Export REST API to export spreadsheet internal object workflows in Ruby. This is a professional solution to export WORKBOOK to WMF format file from spreadsheet online using Ruby." urlsection="export/workbook-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Export WORKBOOK object to WMF format file in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export WORKBOOK object to WMF file from spreadsheet is a complex task. Export WORKBOOK to WMF format transitions is performed by our Ruby SDK while maintaining the source WORKBOOK spreadsheet's main structural and logical content. Our Ruby library is a professional solution to export WORKBOOK objects to WMF format files online. This Cloud SDK gives Ruby developers powerful functionality and perfect WMF output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Ruby using REST API to export WORKBOOK to WMF format from spreadsheet" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::LiteCellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            files = {}      
            name = $DataSourceXlsx
            files[name] = ::File.open(File.expand_path("data/"+name),"r") 
            name =$AssemblyTestXlsx 
            files[name] = ::File.open(File.expand_path("data/"+name),"r")
            format = 'wmf'
            objectType =  'workbook'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Ruby API to export  WORKBOOK to WMF" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call post_export method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}