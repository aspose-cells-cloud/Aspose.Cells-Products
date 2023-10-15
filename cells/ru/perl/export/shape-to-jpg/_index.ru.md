---
title:  Экспортируйте SHAPE в JPG из Excel с помощью Cloud SDK Cells для Perl.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Экспорт SHAPE в JPG из Excel" h2="Perl библиотека для экспорта SHAPE в файл JPG" p="Используйте экспорт API из Cells Cloud для экспорта рабочих процессов внутренних объектов файла Excel в Perl. Это профессиональное решение для экспорта файла формата SHAPE в JPG из электронной таблицы онлайн с использованием Perl." urlsection="export/shape-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспортируйте объект SHAPE в файл формата JPG с помощью Cells Cloud SDK для Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта SHAPE в файл JPG из файла Excel — сложная задача. Экспорт переходов формата SHAPE в JPG выполняется с помощью нашего SDK Perl с сохранением основного структурного и логического содержимого исходной таблицы SHAPE. Наша библиотека Perl — это профессиональное решение для онлайн-экспорта объектов SHAPE в файлы формата JPG. Этот Cloud SDK предоставляет разработчикам Perl мощные функциональные возможности и идеальный вывод в формате JPG.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода Perl с использованием REST API для экспорта SHAPE в формат JPG из электронной таблицы." gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'shape',format => 'jpg');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cloud SDK Cells для Perl для экспорта объектов из Excel SHAPE в JPG." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Вызовите метод post_export, чтобы получить результирующий поток.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
