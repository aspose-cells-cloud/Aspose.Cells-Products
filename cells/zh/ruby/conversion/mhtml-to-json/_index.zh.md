---
title: 使用 Ruby 将 MHTML 转换为 JSON
description: 利用Aspose.Cells Cloud SDK for Ruby将MHTML格式文件转换为JSON格式文件。
kwords: Excel, Convert MHTML to JSON, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert MHTML to JSON using the Cells Cloud Ruby library.","description": "How to convert MHTML to JSON using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/conversion/mhtml-to-json/","step": [{ "@type": "HowToStep","name": "How to convert MHTML to JSON using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/mhtml-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert MHTML to JSON using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/mhtml-to-json/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert MHTML to JSON using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/mhtml-to-json/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to convert MHTML to JSON using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/mhtml-to-json/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 MHTML 转换为 JSON" h2="用于将 MHTML 转换为 JSON 的 Ruby 库" p="使用 Cells Cloud 的 Conversion API 在 Ruby 项目中创建自定义电子表格工作流程。这是使用 Ruby 在线将 MHTML 转换为 JSON 和其他文档格式的专业解决方案。" urlsection="conversion/mhtml-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Ruby 将 MHTML 转换为 JSON" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 MHTML 转换为 JSON 可能是一项复杂的任务。我们的 Ruby SDK 处理所有 MHTML 到 JSON 格式的转换，同时保留源 MHTML 电子表格的主要结构和逻辑内容。我们的 Ruby 库提供了在线将 MHTML 转换为 JSON 文件的专业解决方案。该Cloud SDK为Ruby开发人员提供了强大的功能，并确保高质量的JSON输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 Cells Cloud SDK 将 MHTML 转换为 JSON 的 Ruby 代码示例" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.mhtml"
            format = 'json'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells Cloud Ruby 库将 MHTML 转换为 JSON。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Ruby 库并将引用（导入库）添加到您的项目中。</li>
<li>在 Ruby 中打开源文件。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>红宝石 2.5 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
