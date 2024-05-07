---
title: 使用 Perl 将 XLSM 另存为 DOCX
description: 利用Aspose.Cells Cloud SDK for Perl将XLSM格式文件保存为DOCX格式文件。
kwords: Excel, Save XLSM as DOCX, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSM as DOCX using the Cells Cloud Perl library.","description": "How to save XLSM as DOCX using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/saveas/xlsm-to-docx/","step": [{ "@type": "HowToStep","name": "How to save XLSM as DOCX using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlsm-to-docx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSM as DOCX using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlsm-to-docx/","text": "Install Perl library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSM as DOCX using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlsm-to-docx/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to save XLSM as DOCX using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlsm-to-docx/","text": "Call post_workbook_save_as method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLSM 保存为 DOCX" h2="Perl 用于将 XLSM 保存为 DOCX 的库" p="使用 Cells Cloud 的 SaveAs API 在 Perl 中创建自定义电子表格工作流程。这是一个专业的解决方案，可使用 Perl 在线将 XLSM 保存为 DOCX 和其他文档格式。" urlsection="saveas/xlsm-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 XLSM 文件另存为 Perl 中的 DOCX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSM 中的文件格式保存为 DOCX 是一项复杂的任务。所有 XLSM 到 DOCX 格式的转换均由我们的 Perl SDK 执行，同时保留源 XLSM 电子表格的主要结构和逻辑内容。我们的 Perl 库是在线将 XLSM 保存为 DOCX 文件的专业解决方案。该Cloud SDK为Perl开发者提供了强大的功能和完美的DOCX输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl 使用 REST 将 XLSM 保存为 DOCX 的代码示例 API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.xlsm';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.docx';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells 云 Perl 库将 XLSM 保存为 DOCX。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Perl 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Perl中的源文件。</li>
<li>呼叫帖子_作业簿_save_as 方法来获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
