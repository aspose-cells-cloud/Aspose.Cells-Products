---
title: Export WORKBOOK to SQL from Excel using Cells Cloud SDK for Ruby  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: Excel, workbook, sql, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to SQL","description": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to SQL","image": {"@type": "ImageObject"},"url": "/ruby/export/workbook-to-sql/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to SQL step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/workbook-to-sql/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to SQL step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/workbook-to-sql/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to SQL step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/workbook-to-sql/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Export WORKBOOK to SQL from Excel" h2="Ruby library for exporting WORKBOOK to SQL file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in Ruby. This is a professional solution to export WORKBOOK to SQL format file from spreadsheet online using Ruby." urlsection="export/workbook-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export WORKBOOK object to SQL format file using Cells Cloud SDK for Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export WORKBOOK object to SQL file from Excel file is a complex task. Export WORKBOOK to SQL format transitions is performed by our Ruby SDK while maintaining the source WORKBOOK spreadsheet's main structural and logical content. Our Ruby library is a professional solution to export WORKBOOK objects to SQL format files online. This Cloud SDK gives Ruby developers powerful functionality and perfect SQL output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in Ruby using REST API to export WORKBOOK to SQL format from spreadsheet" gistPath="" %}}
  
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
            objectType =  'workbook'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to SQL" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Call post_export method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
