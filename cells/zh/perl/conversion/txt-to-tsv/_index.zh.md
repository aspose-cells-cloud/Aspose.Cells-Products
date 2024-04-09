---
title: 使用 Perl 将 TXT 转换为 TSV
description: 利用Perl的Aspose.Cells Cloud SDK将TXT格式文件转换为TSV格式文件。
kwords: Excel, Convert TXT to TSV, REST, Perl
howto: How to convert TXT to TSV using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 TXT 转换为 TSV" h2="Perl 用于将 TXT 转换为 TSV 的库" p="使用 Cells 云的转换 API 在 Perl 项目中创建自定义电子表格工作流程。这是使用Perl在线将TXT转换为TSV和其他文档格式的专业解决方案。" urlsection="conversion/txt-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Perl 将 TXT 转换为 TSV" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 TXT 转换为 TSV 可能是一项复杂的任务。我们的 Perl SDK 处理所有 TXT 到 TSV 格式的转换，同时保留源 TXT 电子表格的主要结构和逻辑内容。我们的 Perl 库提供了在线将 TXT 转换为 TSV 文件的专业解决方案。该Cloud SDK为Perl开发者提供了强大的功能，并确保高质量的TSV输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl 使用 Cells Cloud SDK 将 TXT 转换为 TSV 的代码示例" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "tsv";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.txt");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.txt") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.tsv") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Perl 库将 TXT 转换为 TSV。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Perl 包并将引用（导入库）添加到您的项目中。</li>
<li>打开Perl中的源文件。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
