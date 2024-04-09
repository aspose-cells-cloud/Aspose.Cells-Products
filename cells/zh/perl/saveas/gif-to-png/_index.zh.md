---
title: 使用 Perl 将 GIF 保存为 PNG
description: 利用Aspose.Cells Cloud SDK for Perl将GIF格式文件保存为PNG格式文件。
kwords: Excel, Save GIF as PNG, REST, Perl
howto: How to save GIF as PNG using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 GIF 保存为 PNG" h2="Perl 用于将 GIF 保存为 PNG 的库" p="使用Cells云的另存为API在Perl中创建自定义电子表格工作流程。这是使用Perl在线将GIF保存为PNG和其他文档格式的专业解决方案。" urlsection="saveas/gif-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 GIF 文件另存为 Perl 中的 PNG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 GIF 文件格式保存为 PNG 是一项复杂的任务。所有 GIF 到 PNG 格式的转换均由我们的 Perl SDK 执行，同时保留源 GIF 电子表格的主要结构和逻辑内容。我们的 Perl 库是在线将 GIF 保存为 PNG 文件的专业解决方案。此Cloud SDK为Perl开发者提供了强大的功能和完美的PNG输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl 使用 REST 将 GIF 保存为 PNG 的代码示例 API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.gif';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.png';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Perl 库将 GIF 保存为 PNG。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Perl 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Perl中的源文件。</li>
<li>呼叫帖子_作业簿_save_as 方法来获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
