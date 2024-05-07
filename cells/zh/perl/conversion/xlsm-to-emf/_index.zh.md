---
title: 使用 Perl 将 XLSM 转换为 EMF
description: 利用Aspose.Cells Cloud SDK for Perl将XLSM格式文件转换为EMF格式文件。
kwords: Excel, Convert XLSM to EMF, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLSM to EMF using the Cells Cloud Perl library.","description": "How to convert XLSM to EMF using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/conversion/xlsm-to-emf/","step": [{ "@type": "HowToStep","name": "How to convert XLSM to EMF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlsm-to-emf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLSM to EMF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlsm-to-emf/","text": "Install Perl package and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLSM to EMF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlsm-to-emf/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to convert XLSM to EMF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlsm-to-emf/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLSM 转换为 EMF" h2="Perl 用于将 XLSM 转换为 EMF 的库" p="使用 Cells 云的转换 API 在 Perl 项目中创建自定义电子表格工作流程。这是使用Perl在线将XLSM转换为EMF和其他文档格式的专业解决方案。" urlsection="conversion/xlsm-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Perl 将 XLSM 转换为 EMF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLSM 转换为 EMF 可能是一项复杂的任务。我们的 Perl SDK 处理所有 XLSM 到 EMF 格式转换，同时保留源 XLSM 电子表格的主要结构和逻辑内容。我们的 Perl 库提供了在线将 XLSM 转换为 EMF 文件的专业解决方案。该Cloud SDK为Perl开发者提供了强大的功能，并保证了EMF的高质量输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl 使用 Cells Cloud SDK 将 XLSM 转换为 EMF 的代码示例" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "emf";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xlsm");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xlsm") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.emf") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells 云 Perl 库将 XLSM 转换为 EMF。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Perl 包并将引用（导入库）添加到您的项目中。</li>
<li>打开Perl中的源文件。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
