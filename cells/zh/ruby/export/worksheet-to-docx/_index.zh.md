---
title: 使用 Cells Cloud SDK for Ruby 将 WORKSHEET 从 Excel 导出到 DOCX
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="将工作表从 Excel 导出到 DOCX" h2="用于将 WORKSHEET 导出到 DOCX 文件的 Ruby 库" p="使用 Cells Cloud 的 Export API 在 Ruby 中导出 Excel 文件内部对象工作流。这是使用 Ruby 在线将电子表格将 WORKSHEET 导出为 DOCX 格式文件的专业解决方案。" urlsection="export/worksheet-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Ruby 将 WORKSHEET 对象导出为 DOCX 格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 WORKSHEET 对象从 Excel 文件导出到 DOCX 文件是一项复杂的任务。将 WORKSHEET 导出为 DOCX 格式转换由我们的 Ruby SDK 执行，同时保留源 WORKSHEET 电子表格的主要结构和逻辑内容。我们的 Ruby 库是将 WORKSHEET 对象在线导出为 DOCX 格式文件的专业解决方案。该Cloud SDK为Ruby开发人员提供了强大的功能和完美的DOCX输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby 中的代码示例，使用 REST API 将电子表格中的 WORKSHEET 导出为 DOCX 格式" gistPath="" %}}
  
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
            format = 'docx'
            objectType =  'worksheet'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells Cloud SDK for Ruby 将对象从 Excel WORKSHEET 导出到 DOCX" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>调用post_export方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
