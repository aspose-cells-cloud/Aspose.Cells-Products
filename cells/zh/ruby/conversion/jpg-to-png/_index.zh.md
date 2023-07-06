---
title:  JPG 到 PNG 转换 API 为 Ruby
description: 使用Aspose.Cells Cloud SDK for Ruby将JPG格式文件转换为PNG格式文件。
url: /zh/ruby/conversion/jpg-to-png/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API 将 JPG 转换为 PNG" h2="将 JPG 转换为 PNG 的 Ruby 库" p="使用 Cells Conversion REST API 在 Ruby 中创建自定义电子表格工作流程。这是使用Ruby在线将JPG转换为PNG等文档格式的专业解决方案。" urlsection="conversion/jpg-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Ruby 中将 JPG 文件转换为 PNG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 JPG 转换为 PNG 是一项复杂的任务。所有 JPG 到 PNG 格式的转换均由我们的 Ruby SDK 执行，同时保留源 JPG 电子表格的主要结构和逻辑内容。我们的 Ruby 库是在线将 JPG 转换为 PNG 文件的专业解决方案。该Cloud SDK为Ruby开发人员提供了强大的功能和完美的PNG输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ruby 中使用 REST API 将 JPG 转换为 PNG 格式的代码示例" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.jpg"
            format = 'png'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Ruby API将JPG转换为PNG" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>呼叫细胞_作业簿_放_转变_获取结果流的工作簿方法</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
