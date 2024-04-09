---
title: 使用 Ruby 将 XLTM 保存为 JSON
description: 利用Aspose.Cells Cloud SDK for Ruby将XLTM格式文件保存为JSON格式文件。
kwords: Excel, Save XLTM as JSON, REST, Ruby
howto: How to save XLTM as JSON using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLTM 保存为 JSON" h2="用于将 XLTM 保存为 JSON 的 Ruby 库" p="使用 Cells Cloud 的 SaveAs API 在 Ruby 中创建自定义电子表格工作流程。这是使用 Ruby 在线将 XLTM 保存为 JSON 和其他文档格式的专业解决方案。" urlsection="saveas/xltm-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="在 Ruby 中将 XLTM 文件另存为 JSON" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLTM 中的文件格式保存为 JSON 是一项复杂的任务。所有 XLTM 到 JSON 格式的转换均由我们的 Ruby SDK 执行，同时保留源 XLTM 电子表格的主要结构和逻辑内容。我们的 Ruby 库是在线将 XLTM 保存为 JSON 文件的专业解决方案。此 Cloud SDK 为 Ruby 开发人员提供了强大的功能和完美的 JSON 输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 REST 将 XLTM 保存为 JSON 的 Ruby 代码示例 API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.xltm'
    save_options = nil
    newfilename = 'Book1Saveas.json'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Ruby 库将 XLTM 保存为 JSON。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Ruby 库并将引用（导入库）添加到您的项目中。</li>
<li>在 Ruby 中打开源文件。</li>
<li>使用 `post_workbook_save_as` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
