---
title: Save FODS as XLSX using Ruby 
description: Utilizing Aspose.Cells Cloud SDK for Ruby to save FODS format file as XLSX format file. 
kwords: Excel, Save FODS as XLSX, REST, Ruby
howto: How to save FODS as XLSX using Aspose.Cells Cloud Ruby library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save FODS as XLSX" h2="Ruby library for saving FODS as XLSX" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Ruby. This is a professional solution to save FODS as XLSX and other document formats online using Ruby." urlsection="saveas/fods-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a FODS file as XLSX in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from FODS as XLSX is a complex task. All FODS to XLSX format transitions is performed by our Ruby SDK while maintaining the source FODS spreadsheet's main structural and logical content. Our Ruby library is a professional solution to save FODS as XLSX files online. This Cloud SDK gives Ruby developers powerful functionality and perfect XLSX output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Example for saving FODS as XLSX using REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.fods'
    save_options = nil
    newfilename = 'Book1Saveas.xlsx'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save FODS as XLSX using the Cells Cloud Ruby library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Ruby library and add the reference (import the library) to your project.</li>
<li>Open the source file in Ruby.</li>
<li>Use the `post_workbook_save_as` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
