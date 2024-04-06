---
title: Save ODS as TIFF using Ruby 
description: Utilizing Aspose.Cells Cloud SDK for Ruby to save ODS format file as TIFF format file. 
kwords: Excel, Save ODS as TIFF, REST, Ruby
howto: How to save ODS as TIFF using Aspose.Cells Cloud Ruby library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save ODS as TIFF" h2="Ruby library for saving ODS as TIFF" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Ruby. This is a professional solution to save ODS as TIFF and other document formats online using Ruby." urlsection="saveas/ods-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a ODS file as TIFF in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from ODS as TIFF is a complex task. All ODS to TIFF format transitions is performed by our Ruby SDK while maintaining the source ODS spreadsheet's main structural and logical content. Our Ruby library is a professional solution to save ODS as TIFF files online. This Cloud SDK gives Ruby developers powerful functionality and perfect TIFF output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Example for saving ODS as TIFF using REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.ods'
    save_options = nil
    newfilename = 'Book1Saveas.tiff'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save ODS as TIFF using the Cells Cloud Ruby library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Ruby library and add the reference (import the library) to your project.</li>
<li>Open the source file in Ruby.</li>
<li>Use the `post_workbook_save_as` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
