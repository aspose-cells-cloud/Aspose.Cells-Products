---
title: 使用 Perl 将 TXT 保存为 XLSB
description: 利用Aspose.Cells Cloud SDK for Perl将TXT格式文件保存为XLSB格式文件。
kwords: Excel, Save TXT as XLSB, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save TXT as XLSB using the Cells Cloud Perl library.","description": "How to save TXT as XLSB using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/saveas/txt-to-xlsb/","step": [{ "@type": "HowToStep","name": "How to save TXT as XLSB using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/txt-to-xlsb/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save TXT as XLSB using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/txt-to-xlsb/","text": "Install Perl library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save TXT as XLSB using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/txt-to-xlsb/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to save TXT as XLSB using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/txt-to-xlsb/","text": "Call post_workbook_save_as method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 TXT 保存为 XLSB" h2="Perl 用于将 TXT 保存为 XLSB 的库" p="使用Cells云的SaveAs API在Perl中创建自定义电子表格工作流程。这是使用Perl在线将TXT保存为XLSB和其他文档格式的专业解决方案。" urlsection="saveas/txt-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 TXT 文件另存为 XLSB 中的 Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 TXT 文件格式保存为 XLSB 是一项复杂的任务。所有 TXT 到 XLSB 格式的转换均由我们的 Perl SDK 执行，同时保留源 TXT 电子表格的主要结构和逻辑内容。我们的 Perl 库是在线将 TXT 保存为 XLSB 文件的专业解决方案。该Cloud SDK为Perl开发人员提供了强大的功能和完美的XLSB输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl 使用 REST 将 TXT 保存为 XLSB 的代码示例 API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.txt';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.xlsb';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells 云 Perl 库将 TXT 保存为 XLSB。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Perl 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Perl中的源文件。</li>
<li>呼叫帖子_作业簿_save_as 方法来获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
