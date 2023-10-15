---
title: 使用 Perl 将 TSV 保存为 XLSM
description: 利用Aspose.Cells Cloud SDK for Perl将TSV格式文件保存为XLSM格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 TSV 保存为 XLSM" h2="Perl 用于将 TSV 保存为 XLSM 的库" p="使用Cells云的SaveAs API在Perl中创建自定义电子表格工作流程。这是使用Perl在线将TSV保存为XLSM和其他文档格式的专业解决方案。" urlsection="saveas/tsv-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 TSV 文件另存为 Perl 中的 XLSM" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 TSV 文件格式保存为 XLSM 是一项复杂的任务。所有 TSV 到 XLSM 格式的转换均由我们的 Perl SDK 执行，同时保留源 TSV 电子表格的主要结构和逻辑内容。我们的 Perl 库是在线将 TSV 保存为 XLSM 文件的专业解决方案。该Cloud SDK为Perl开发人员提供了强大的功能和完美的XLSM输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl 使用 REST 将 TSV 保存为 XLSM 的代码示例 API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.tsv';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.xlsm';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Perl将Excel文件保存为其他格式TSV为XLSM" >}}
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
