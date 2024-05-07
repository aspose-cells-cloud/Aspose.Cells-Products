---
title: 使用 Cells Cloud SDK for Perl 将 WORKBOOK 从 Excel 导出到 EMF
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
kwords: Excel, workbook, emf, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to EMF","description": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to EMF","image": {"@type": "ImageObject"},"url": "/perl/export/workbook-to-emf/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to EMF step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-emf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to EMF step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-emf/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to EMF step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-emf/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将工作簿从 Excel 导出到 EMF" h2="Perl 库用于将 WORKBOOK 导出到 EMF 文件" p="使用 Cells 云的导出 API 导出 Perl 中的 Excel 文件内部对象工作流。这是一个专业的解决方案，可使用 Perl 在线将电子表格中的 WORKBOOK 导出为 EMF 格式的文件。" urlsection="export/workbook-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Perl 将 WORKBOOK 对象导出为 EMF 格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 WORKBOOK 对象从 Excel 文件导出到 EMF 文件是一项复杂的任务。将 WORKBOOK 导出到 EMF 格式的转换由我们的 Perl SDK 执行，同时保留源 WORKBOOK 电子表格的主要结构和逻辑内容。我们的 Perl 库是一个专业的解决方案，可在线将 WORKBOOK 对象导出到 EMF 格式的文件。此云 SDK 为 Perl 开发人员提供了强大的功能和完美的 EMF 输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl 中的代码示例使用 REST API 将电子表格中的 WORKBOOK 导出为 EMF 格式" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use MIME::Base64;
    use AsposeCellsCloud::LightCellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::LightCellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $filemap = { 'Book1.xlsx' => '~/TestData/Book1.xlsx', 'myDocument.xlsx' => ~/TestData/myDocument.xlsx'};
    my $result = $instance->post_export(file => $filemap , object_type => 'workbook',format => 'emf');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Perl将对象从Excel WORKBOOK导出到EMF" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>调用post_export方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
