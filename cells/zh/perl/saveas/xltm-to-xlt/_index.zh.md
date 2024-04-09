---
title: 使用 Perl 将 XLTM 保存为 XLT
description: 利用Aspose.Cells Cloud SDK for Perl将XLTM格式文件保存为XLT格式文件。
kwords: Excel, Save XLTM as XLT, REST, Perl
howto: How to save XLTM as XLT using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLTM 保存为 XLT" h2="Perl 用于将 XLTM 保存为 XLT 的库" p="使用Cells云的SaveAs API在Perl中创建自定义电子表格工作流程。这是使用Perl在线将XLTM保存为XLT和其他文档格式的专业解决方案。" urlsection="saveas/xltm-to-xlt/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 XLTM 文件另存为 Perl 中的 XLT" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLTM 的文件格式保存为 XLT 是一项复杂的任务。所有 XLTM 到 XLT 格式的转换均由我们的 Perl SDK 执行，同时保留源 XLTM 电子表格的主要结构和逻辑内容。我们的 Perl 库是在线将 XLTM 保存为 XLT 文件的专业解决方案。该Cloud SDK为Perl开发人员提供了强大的功能和完美的XLT输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl 使用 REST 将 XLTM 保存为 XLT 的代码示例 API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.xltm';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.xlt';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Perl 库将 XLTM 另存为 XLT。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Perl 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Perl中的源文件。</li>
<li>呼叫帖子_作业簿_save_as 方法来获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
