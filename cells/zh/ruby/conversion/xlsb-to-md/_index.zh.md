---
title: 使用 Ruby 将 XLSB 转换为 MD
description: 使用Aspose.Cells Cloud SDK for Ruby将XLSB格式文件转换为MD格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 XLSB 转换为 MD" h2="用于将 XLSB 转换为 MD 的 Ruby 库" p="使用 Cells Cloud 的 Conversion API 在 Ruby 项目中创建自定义电子表格工作流程。这是使用 Ruby 在线将 XLSB 转换为 MD 和其他文档格式的专业解决方案。" urlsection="conversion/xlsb-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="使用 Cells Cloud SDK for Ruby 将 XLSB 转换为 MD" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLSB 转换为 MD 可能是一项复杂的任务。我们的 Ruby SDK 处理所有 XLSB 到 MD 格式的转换，同时保留源 XLSB 电子表格的主要结构和逻辑内容。我们的 Ruby 库提供了在线将 XLSB 转换为 MD 文件的专业解决方案。该Cloud SDK为Ruby开发人员提供了强大的功能，并确保高质量的MD输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="使用 Cells Cloud SDK 将 XLSB 转换为 MD 的 Ruby 代码示例" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlsb"
            format = 'md'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Ruby将Excel文件转换为其他格式XLSB转MD" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
