---
title: 使用 Ruby 将 XLTX 转换为 SVG
description: 利用Aspose.Cells Cloud SDK for Ruby将XLTX格式文件转换为SVG格式文件。
kwords: Excel, Convert XLTX to SVG, REST, Ruby
howto: How to convert XLTX to SVG using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLTX 转换为 SVG" h2="用于将 XLTX 转换为 SVG 的 Ruby 库" p="使用 Cells Cloud 的 Conversion API 在 Ruby 项目中创建自定义电子表格工作流程。这是使用 Ruby 在线将 XLTX 转换为 SVG 等文档格式的专业解决方案。" urlsection="conversion/xltx-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Ruby 将 XLTX 转换为 SVG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLTX 转换为 SVG 可能是一项复杂的任务。我们的 Ruby SDK 处理所有 XLTX 到 SVG 格式的转换，同时保留源 XLTX 电子表格的主要结构和逻辑内容。我们的 Ruby 库提供了在线将 XLTX 转换为 SVG 文件的专业解决方案。该Cloud SDK为Ruby开发人员提供了强大的功能，并确保高质量的SVG输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 Cells Cloud SDK 将 XLTX 转换为 SVG 的 Ruby 代码示例" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xltx"
            format = 'svg'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Ruby 库将 XLTX 转换为 SVG。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Ruby 库并将引用（导入库）添加到您的项目中。</li>
<li>在 Ruby 中打开源文件。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
