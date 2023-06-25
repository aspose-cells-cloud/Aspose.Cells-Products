---
title: 使用 Ruby 将电子表格中的 SHAPE 导出为 WMF API
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
url: /zh/ruby/export/shape-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API 将 SHAPE 导出到 WMF 文件" h2="用于将 SHAPE 导出到 WMF 文件的 Ruby 库" p="使用 Cells Export REST API 在 Ruby 中导出电子表格内部对象工作流程。这是使用 Ruby 将电子表格在线导出 SHAPE 为 WMF 格式文件的专业解决方案。" urlsection="export/shape-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Ruby 中将 SHAPE 对象导出为 WMF 格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 SHAPE 对象从电子表格导出到 WMF 文件是一项复杂的任务。将 SHAPE 导出为 WMF 格式转换由我们的 Ruby SDK 执行，同时保留源 SHAPE 电子表格的主要结构和逻辑内容。我们的 Ruby 库是将 SHAPE 对象在线导出为 WMF 格式文件的专业解决方案。此 Cloud SDK 为 Ruby 开发人员提供了强大的功能和完美的 WMF 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ruby 中的代码示例，使用 REST API 将电子表格中的 SHAPE 导出为 WMF 格式" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::LiteCellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            files = {}      
            name = $DataSourceXlsx
            files[name] = ::File.open(File.expand_path("data/"+name),"r") 
            name =$AssemblyTestXlsx 
            files[name] = ::File.open(File.expand_path("data/"+name),"r")
            format = 'wmf'
            objectType =  'shape'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Ruby API 将 SHAPE 导出为 WMF" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用post_export方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
