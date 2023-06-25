---
title:  PNG 至 PDF 将 API 转换为 Perl
description: 使用Aspose.Cells Cloud SDK for Perl将PNG格式文件转换为PDF格式文件。
url: /zh/perl/conversion/png-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API 将 PNG 转换为 PDF" h2="Perl库将PNG转换为PDF" p="使用Cells转换REST API在Perl中创建自定义电子表格工作流程。这是使用Perl在线将PNG转换为PDF和其他文档格式的专业解决方案。" urlsection="conversion/png-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 PNG 文件转换为 Perl 中的 PDF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 PNG 转换为 PDF 是一项复杂的任务。所有 PNG 到 PDF 格式转换均由我们的 Perl SDK 执行，同时保留源 PNG 电子表格的主要结构和逻辑内容。我们的 Perl 库是在线将 PNG 转换为 PDF 文件的专业解决方案。此Cloud SDK为Perl开发者提供了强大的功能和完美的PDF输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl 中的代码示例使用 REST API 将 PNG 转换为 PDF 格式" gistPath="" %}}
 
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
    my @fileinfos = stat("Book1.png");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.png") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.pdf") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Perl API 将 PNG 转换为 PDF" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>呼叫细胞_作业簿_放_转变_获取结果流的工作簿方法</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
