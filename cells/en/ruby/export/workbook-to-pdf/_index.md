---
title: Export WORKBOOK to PDF from Excel using Cells Cloud SDK for Ruby  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: 
howto: 
---


{{< blocks/products/cells/cells-cloud-banner h1="Export WORKBOOK to PDF from Excel" h2="Ruby library for exporting WORKBOOK to PDF file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in Ruby. This is a professional solution to export WORKBOOK to PDF format file from spreadsheet online using Ruby." urlsection="export/workbook-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export WORKBOOK object to PDF format file using Cells Cloud SDK for Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export WORKBOOK object to PDF file from Excel file is a complex task. Export WORKBOOK to PDF format transitions is performed by our Ruby SDK while maintaining the source WORKBOOK spreadsheet's main structural and logical content. Our Ruby library is a professional solution to export WORKBOOK objects to PDF format files online. This Cloud SDK gives Ruby developers powerful functionality and perfect PDF output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in Ruby using REST API to export WORKBOOK to PDF format from spreadsheet" gistPath="" %}}
  
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
            format = 'pdf'
            objectType =  'workbook'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to PDF" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Call post_export method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
