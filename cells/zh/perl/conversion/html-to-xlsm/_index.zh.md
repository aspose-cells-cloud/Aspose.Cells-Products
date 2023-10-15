---
title: 使用 Perl 将 HTML 转换为 XLSM
description: 利用Aspose.Cells Cloud SDK for Perl将HTML格式文件转换为XLSM格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 HTML 转换为 XLSM" h2="用于将 HTML 转换为 XLSM 的 Perl 库" p="使用 Cells 云的转换 API 在 Perl 项目中创建自定义电子表格工作流程。这是使用Perl在线将HTML转换为XLSM和其他文档格式的专业解决方案。" urlsection="conversion/html-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="使用 Cells Cloud SDK for Perl 将 HTML 转换为 XLSM" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 HTML 转换为 XLSM 可能是一项复杂的任务。我们的 Perl SDK 处理所有 HTML 到 XLSM 格式的转换，同时保留源 HTML 电子表格的主要结构和逻辑内容。我们的 Perl 库提供了在线将 HTML 转换为 XLSM 文件的专业解决方案。该Cloud SDK为Perl开发者提供了强大的功能，并确保高质量的XLSM输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl 使用 Cells Cloud SDK 将 HTML 转换为 XLSM 的代码示例" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xlsm";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.html");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.html") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xlsm") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Perl SDK将HTML转换为XLSM" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
