---
title: Save ODS as WMF API for Ruby 
description: Using Aspose.Cells Cloud SDK for Ruby to save ODS format file as WMF format file. 
url: /ruby/saveas/ods-to-wmf/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API to save ODS as WMF" h2="Ruby library to save ODS as WMF" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in Ruby. This is a professional solution to save ODS as WMF and other document formats online using Ruby." urlsection="saveas/ods-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a ODS file as WMF in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from ODS as WMF is a complex task. All ODS to WMF format transitions is performed by our Ruby SDK while maintaining the source ODS spreadsheet's main structural and logical content. Our Ruby library is a professional solution to save ODS as WMF files online. This Cloud SDK gives Ruby developers powerful functionality and perfect WMF output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Ruby using REST API to save ODS as WMF format" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.ods'
    save_options = nil
    newfilename = 'Book1Saveas.wmf'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Ruby API to save  ODS as WMF" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cells_save_as_post_document_save_as method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>ruby 2.5 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
