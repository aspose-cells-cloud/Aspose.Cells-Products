---
title: 使用 Ruby 将 ODS 保存为 BMP
description: 利用 Aspose.Cells Cloud SDK for Ruby 将 ODS 格式文件保存为 BMP 格式文件。
kwords: Excel, Save ODS as BMP, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save ODS as BMP using the Cells Cloud Ruby library.","description": "How to save ODS as BMP using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/ods-to-bmp/","step": [{ "@type": "HowToStep","name": "How to save ODS as BMP using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-bmp/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save ODS as BMP using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-bmp/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save ODS as BMP using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-bmp/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save ODS as BMP using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-bmp/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 ODS 保存为 BMP" h2="用于将 ODS 保存为 BMP 的 Ruby 库" p="使用 Cells Cloud 的 SaveAs API 在 Ruby 中创建自定义电子表格工作流。这是使用 Ruby 在线将 ODS 保存为 BMP 和其他文档格式的专业解决方案。" urlsection="saveas/ods-to-bmp/" >}}

{{< blocks/products/cells/cells-cloud-section title="在 Ruby 中将 ODS 文件保存为 BMP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 ODS 中的文件格式保存为 BMP 是一项复杂的任务。所有 ODS 到 BMP 格式的转换均由我们的 Ruby SDK 执行，同时保留源 ODS 电子表格的主要结构和逻辑内容。我们的 Ruby 库是在线将 ODS 保存为 BMP 文件的专业解决方案。该Cloud SDK为Ruby开发人员提供了强大的功能和完美的BMP输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 REST API 将 ODS 保存为 BMP 的 Ruby 代码示例" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.ods'
    save_options = nil
    newfilename = 'Book1Saveas.bmp'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells Cloud Ruby 库将 ODS 保存为 BMP。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Ruby 库并将引用（导入库）添加到您的项目中。</li>
<li>在 Ruby 中打开源文件。</li>
<li>使用 `post_workbook_save_as` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
