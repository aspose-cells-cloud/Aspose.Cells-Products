﻿---
title: 使用 Perl 将 XLSB 保存为 CSV
description: 利用Aspose.Cells Cloud SDK for Perl将XLSB格式文件保存为CSV格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 XLSB 保存为 CSV" h2="Perl 用于将 XLSB 保存为 CSV 的库" p="使用 Cells Cloud 的 SaveAs API 在 Perl 中创建自定义电子表格工作流程。这是一个专业的解决方案，可使用 Perl 在线将 XLSB 保存为 CSV 和其他文档格式。" urlsection="saveas/xlsb-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 XLSB 文件另存为 Perl 中的 CSV" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSB 中的文件格式保存为 CSV 是一项复杂的任务。所有 XLSB 到 CSV 格式的转换均由我们的 Perl SDK 执行，同时保留源 XLSB 电子表格的主要结构和逻辑内容。我们的 Perl 库是在线将 XLSB 保存为 CSV 文件的专业解决方案。该Cloud SDK为Perl开发人员提供了强大的功能和完美的CSV输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl 使用 REST 将 XLSB 保存为 CSV 的代码示例 API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.xlsb';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.csv';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Perl将Excel文件保存为其他格式XLSB为CSV" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>呼叫帖子_作业簿_save_as 方法来获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
