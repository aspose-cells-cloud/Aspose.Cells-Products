---
title: 使用 Ruby 将 XLSM 保存为 PPTX
description: 利用Aspose.Cells Cloud SDK for Ruby将XLSM格式文件保存为PPTX格式文件。
kwords: Excel, Save XLSM as PPTX, REST, Ruby
howto: How to save XLSM as PPTX using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLSM 保存为 PPTX" h2="用于将 XLSM 保存为 PPTX 的 Ruby 库" p="使用 Cells Cloud 的 SaveAs API 在 Ruby 中创建自定义电子表格工作流程。这是使用 Ruby 在线将 XLSM 保存为 PPTX 和其他文档格式的专业解决方案。" urlsection="saveas/xlsm-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="在 Ruby 中将 XLSM 文件另存为 PPTX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSM 中的文件格式另存为 PPTX 是一项复杂的任务。所有 XLSM 到 PPTX 格式的转换均由我们的 Ruby SDK 执行，同时保留源 XLSM 电子表格的主要结构和逻辑内容。我们的 Ruby 库是在线将 XLSM 保存为 PPTX 文件的专业解决方案。该Cloud SDK为Ruby开发人员提供了强大的功能和完美的PPTX输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 REST 将 XLSM 保存为 PPTX 的 Ruby 代码示例 API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.xlsm'
    save_options = nil
    newfilename = 'Book1Saveas.pptx'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Ruby 库将 XLSM 保存为 PPTX。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Ruby 库并将引用（导入库）添加到您的项目中。</li>
<li>在 Ruby 中打开源文件。</li>
<li>使用 `post_workbook_save_as` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
