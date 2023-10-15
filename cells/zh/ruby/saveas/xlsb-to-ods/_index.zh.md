---
title: 使用 Ruby 将 XLSB 保存为 ODS
description: 利用Aspose.Cells Cloud SDK for Ruby将XLSB格式文件保存为ODS格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 XLSB 保存为 ODS" h2="用于将 XLSB 保存为 ODS 的 Ruby 库" p="使用 Cells Cloud 的 SaveAs API 在 Ruby 中创建自定义电子表格工作流程。这是使用 Ruby 在线将 XLSB 保存为 ODS 和其他文档格式的专业解决方案。" urlsection="saveas/xlsb-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Ruby 中将 XLSB 文件另存为 ODS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSB 中的文件格式保存为 ODS 是一项复杂的任务。所有 XLSB 到 ODS 格式的转换均由我们的 Ruby SDK 执行，同时保留源 XLSB 电子表格的主要结构和逻辑内容。我们的 Ruby 库是在线将 XLSB 保存为 ODS 文件的专业解决方案。该Cloud SDK为Ruby开发人员提供了强大的功能和完美的ODS输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="使用 REST 将 XLSB 保存为 ODS 的 Ruby 代码示例 API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.xlsb'
    save_options = nil
    newfilename = 'Book1Saveas.ods'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Ruby将Excel文件另存为其他格式XLSB为ODS" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `post_workbook_save_as` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
