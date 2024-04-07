---
title: Export LISTOBJECT to SQL from Excel using Cells Cloud SDK for Ruby  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: 
howto: 
---


{{< blocks/products/cells/cells-cloud-banner h1="Export LISTOBJECT to SQL from Excel" h2="Ruby library for exporting LISTOBJECT to SQL file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in Ruby. This is a professional solution to export LISTOBJECT to SQL format file from spreadsheet online using Ruby." urlsection="export/listobject-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export LISTOBJECT object to SQL format file using Cells Cloud SDK for Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export LISTOBJECT object to SQL file from Excel file is a complex task. Export LISTOBJECT to SQL format transitions is performed by our Ruby SDK while maintaining the source LISTOBJECT spreadsheet's main structural and logical content. Our Ruby library is a professional solution to export LISTOBJECT objects to SQL format files online. This Cloud SDK gives Ruby developers powerful functionality and perfect SQL output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in Ruby using REST API to export LISTOBJECT to SQL format from spreadsheet" gistPath="" %}}
  
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
            format = 'sql'
            objectType =  'listobject'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Ruby to export objects from Excel LISTOBJECT to SQL" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Call post_export method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
