---
title: 使用 Perl 将 XLTX 转换为 PDF
description: 利用Aspose.Cells Cloud SDK for Perl将XLTX格式文件转换为PDF格式文件。
kwords: Excel, Convert XLTX to PDF, REST, Perl
howto: How to convert XLTX to PDF using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLTX 转换为 PDF" h2="Perl 用于将 XLTX 转换为 PDF 的库" p="使用 Cells 云的转换 API 在 Perl 项目中创建自定义电子表格工作流程。这是使用Perl在线将XLTX转换为PDF和其他文档格式的专业解决方案。" urlsection="conversion/xltx-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Perl 将 XLTX 转换为 PDF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLTX 转换为 PDF 可能是一项复杂的任务。我们的 Perl SDK 处理所有 XLTX 到 PDF 格式转换，同时保留源 XLTX 电子表格的主要结构和逻辑内容。我们的 Perl 库提供了在线将 XLTX 转换为 PDF 文件的专业解决方案。该Cloud SDK为Perl开发者提供了强大的功能，并保证了PDF的高质量输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl 使用 Cells Cloud SDK 将 XLTX 转换为 PDF 的代码示例" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "pdf";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xltx");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xltx") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.pdf") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells 云 Perl 库将 XLTX 转换为 PDF。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Perl 包并将引用（导入库）添加到您的项目中。</li>
<li>打开Perl中的源文件。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
