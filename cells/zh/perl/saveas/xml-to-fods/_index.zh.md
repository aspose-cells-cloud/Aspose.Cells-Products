﻿---
title: 将 XML 另存为 Perl 的 FODS API
description: 用于 Microsoft Excel 和 OpenOffice Calc 的云 API 和 SDK。将电子表格转换为其他格式文件。
url: /zh/perl/saveas/xml-to-fods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API 将 XML 保存为 FODS" h2="Perl 将 XML 保存为 FODS 的库" p="使用Cells SaveAs REST API 在Perl创建自定义电子表格工作流。这是使用Perl在线将XML保存为FODS和其他文档格式的专业解决方案。" urlsection="saveas/xml-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Perl 中将 XML 文件另存为 FODS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XML 文件格式保存为 FODS 是一项复杂的任务。所有 XML 到 FODS 格式的转换都由我们的 Perl SDK 执行，同时保持源 XML 电子表格的主要结构和逻辑内容。我们的 Perl 库是将 XML 在线保存为 FODS 文件的专业解决方案。此 Cloud SDK 为 Perl 开发人员提供了强大的功能和完美的 FODS 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl 中的代码示例使用 REST API 将 XML 保存为 FODS 格式" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.xml';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.fods';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Perl API将XML保存为FODS" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>通话单元_节省_作为_邮政_文档_节省_作为获取结果流的方法</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}