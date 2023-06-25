---
title: 将 JPG 保存为 SQL API 为 Perl
description: 使用Aspose.Cells Cloud SDK for Perl将JPG格式文件保存为SQL格式文件。
url: /zh/perl/saveas/jpg-to-sql/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API 将JPG保存为SQL" h2="Perl 将 JPG 保存为 SQL 的库" p="使用Cells SaveAs REST API在Perl中创建自定义电子表格工作流程。这是使用Perl在线将JPG保存为SQL和其他文档格式的专业解决方案。" urlsection="saveas/jpg-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 JPG 文件另存为 Perl 中的 SQL" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 JPG 文件格式保存为 SQL 是一项复杂的任务。所有 JPG 到 SQL 格式的转换均由我们的 Perl SDK 执行，同时保留源 JPG 电子表格的主要结构和逻辑内容。我们的 Perl 库是在线将 JPG 保存为 SQL 文件的专业解决方案。此Cloud SDK为Perl开发者提供了强大的功能和完美的SQL输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl 中的代码示例使用 REST API 将 JPG 保存为 SQL 格式" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.jpg';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.sql';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Perl API将JPG保存为SQL" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>呼叫细胞_节省_作为_邮政_文档_节省_as 获取结果流的方法</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
