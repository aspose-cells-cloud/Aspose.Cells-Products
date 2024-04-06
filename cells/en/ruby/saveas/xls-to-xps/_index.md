---
title: Save XLS as XPS using Ruby 
description: Utilizing Aspose.Cells Cloud SDK for Ruby to save XLS format file as XPS format file. 
kwords: Excel, Save XLS as XPS, REST, Ruby
howto: How to save XLS as XPS using Aspose.Cells Cloud Ruby library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save XLS as XPS" h2="Ruby library for saving XLS as XPS" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Ruby. This is a professional solution to save XLS as XPS and other document formats online using Ruby." urlsection="saveas/xls-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a XLS file as XPS in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLS as XPS is a complex task. All XLS to XPS format transitions is performed by our Ruby SDK while maintaining the source XLS spreadsheet's main structural and logical content. Our Ruby library is a professional solution to save XLS as XPS files online. This Cloud SDK gives Ruby developers powerful functionality and perfect XPS output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Example for saving XLS as XPS using REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.xls'
    save_options = nil
    newfilename = 'Book1Saveas.xps'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save XLS as XPS using the Cells Cloud Ruby library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Ruby library and add the reference (import the library) to your project.</li>
<li>Open the source file in Ruby.</li>
<li>Use the `post_workbook_save_as` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
