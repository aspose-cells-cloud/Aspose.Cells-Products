﻿---
title:  XLTM 到 PPTX 转换 API 为 Perl
description: 用于 Microsoft Excel 和 OpenOffice Calc 的云 API 和 SDK。将电子表格转换为其他格式文件。
url: /zh/perl/conversion/xltm-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API 将 XLTM 转换为 PPTX" h2="Perl 将 XLTM 转换为 PPTX 的库" p="使用 Cells Conversion REST API 在 Perl 中创建自定义电子表格工作流程。这是使用 Perl 在线将 XLTM 转换为 PPTX 和其他文档格式的专业解决方案。" urlsection="conversion/xltm-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Perl 中将 XLTM 文件转换为 PPTX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLTM 转换为 PPTX 是一项复杂的任务。所有 XLTM 到 PPTX 格式的转换都由我们的 Perl SDK 执行，同时保持源 XLTM 电子表格的主要结构和逻辑内容。我们的 Perl 库是在线将 XLTM 文件转换为 PPTX 文件的专业解决方案。此 Cloud SDK 为 Perl 开发人员提供了强大的功能和完美的 PPTX 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl 中的代码示例使用 REST API 将 XLTM 转换为 PPTX 格式" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "pptx";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xltm");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xltm") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.pptx") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Perl API将XLTM转换成PPTX" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>通话单元_工作簿_放_转变_获取结果流的工作簿方法</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}