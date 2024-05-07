---
title:  Экспортируйте SHAPE в WMF из Excel с помощью Cloud SDK Cells для Perl.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords: Excel, shape, wmf, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Perl to export objects from Excel SHAPE to WMF","description": "How to use Cells Cloud SDK for Perl to export objects from Excel SHAPE to WMF","image": {"@type": "ImageObject"},"url": "/perl/export/shape-to-wmf/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel SHAPE to WMF step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/shape-to-wmf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel SHAPE to WMF step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/shape-to-wmf/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel SHAPE to WMF step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/shape-to-wmf/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспорт SHAPE в WMF с номера Excel" h2="Perl библиотека для экспорта SHAPE в файл WMF" p="Используйте экспорт API из Cells Cloud для экспорта рабочих процессов внутренних объектов файла Excel в Perl. Это профессиональное решение для экспорта SHAPE в файл формата WMF из электронной таблицы онлайн с использованием Perl." urlsection="export/shape-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект SHAPE в файл формата WMF с помощью Cells Cloud SDK для Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта SHAPE в файл WMF из файла Excel — сложная задача. Экспорт переходов формата SHAPE в WMF выполняется с помощью нашего SDK Perl с сохранением основного структурного и логического содержимого исходной таблицы SHAPE. Наша библиотека Perl — это профессиональное решение для онлайн-экспорта объектов SHAPE в файлы формата WMF. Этот Cloud SDK предоставляет разработчикам Perl мощные функциональные возможности и отличный результат в формате WMF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода в Perl с использованием REST API для экспорта SHAPE в формат WMF из электронной таблицы" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'shape',format => 'wmf');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Perl для экспорта объектов из Excel SHAPE в WMF" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Вызовите метод post_export, чтобы получить результирующий поток.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
