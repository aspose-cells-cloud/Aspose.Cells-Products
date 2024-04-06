---
title: Save JSON as DOCX using Ruby 
description: Utilizing Aspose.Cells Cloud SDK for Ruby to save JSON format file as DOCX format file. 
kwords: Excel, Save JSON as DOCX, REST, Ruby
howto: How to save JSON as DOCX using Aspose.Cells Cloud Ruby library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save JSON as DOCX" h2="Ruby library for saving JSON as DOCX" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Ruby. This is a professional solution to save JSON as DOCX and other document formats online using Ruby." urlsection="saveas/json-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a JSON file as DOCX in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from JSON as DOCX is a complex task. All JSON to DOCX format transitions is performed by our Ruby SDK while maintaining the source JSON spreadsheet's main structural and logical content. Our Ruby library is a professional solution to save JSON as DOCX files online. This Cloud SDK gives Ruby developers powerful functionality and perfect DOCX output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Example for saving JSON as DOCX using REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.json'
    save_options = nil
    newfilename = 'Book1Saveas.docx'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save JSON as DOCX using the Cells Cloud Ruby library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Ruby library and add the reference (import the library) to your project.</li>
<li>Open the source file in Ruby.</li>
<li>Use the `post_workbook_save_as` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
