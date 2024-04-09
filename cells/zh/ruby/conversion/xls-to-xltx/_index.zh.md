---
title: 使用 Ruby 将 XLS 转换为 XLTX
description: 使用Aspose.Cells Cloud SDK for Ruby将XLS格式文件转换为XLTX格式文件。
kwords: Excel, Convert XLS to XLTX, REST, Ruby
howto: How to convert XLS to XLTX using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLS 转换为 XLTX" h2="用于将 XLS 转换为 XLTX 的 Ruby 库" p="使用 Cells Cloud 的 Conversion API 在 Ruby 项目中创建自定义电子表格工作流程。这是使用 Ruby 在线将 XLS 转换为 XLTX 和其他文档格式的专业解决方案。" urlsection="conversion/xls-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Ruby 将 XLS 转换为 XLTX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLS 转换为 XLTX 可能是一项复杂的任务。我们的 Ruby SDK 处理所有 XLS 到 XLTX 格式的转换，同时保留源 XLS 电子表格的主要结构和逻辑内容。我们的 Ruby 库提供了在线将 XLS 转换为 XLTX 文件的专业解决方案。该 Cloud SDK 为 Ruby 开发人员提供了强大的功能，并确保高质量的 XLTX 输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 Cells Cloud SDK 将 XLS 转换为 XLTX 的 Ruby 代码示例" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xls"
            format = 'xltx'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Ruby 库将 XLS 转换为 XLTX。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Ruby 库并将引用（导入库）添加到您的项目中。</li>
<li>在 Ruby 中打开源文件。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
