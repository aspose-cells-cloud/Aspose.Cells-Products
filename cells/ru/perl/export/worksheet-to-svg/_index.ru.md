---
title:  Экспорт WORKSHEET в SVG из электронной таблицы с использованием Perl API
description:  Aspose.Cells Cloud REST API поддерживает экспорт {0} в файлы формата {1} с использованием {2}.
url: /ru/perl/export/worksheet-to-svg/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API для экспорта РАБОЧЕЙ ТАБЛИЦЫ в файл SVG" h2="Библиотека Perl для экспорта WORKSHEET в файл SVG" p="Используйте Cells Export REST API для экспорта рабочих процессов внутренних объектов электронной таблицы в Perl. Это профессиональное решение для экспорта файла формата WORKSHEET в SVG из электронной таблицы онлайн с использованием Perl." urlsection="export/worksheet-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспорт объекта WORKSHEET в файл формата SVG в Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта WORKSHEET в файл SVG из электронной таблицы является сложной задачей. Экспорт WORKSHEET в переходы формата SVG выполняется нашим SDK Perl, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы WORKSHEET. Наша библиотека Perl — это профессиональное решение для экспорта объектов WORKSHEET в файлы формата SVG онлайн. Этот облачный SDK предоставляет Perl разработчикам мощную функциональность и идеальный результат SVG.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Perl с использованием REST API для экспорта WORKSHEET в формат SVG из электронной таблицы" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'worksheet',format => 'svg');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Perl API для экспорта РАБОЧЕЙ ТАБЛИЦЫ в SVG" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод post_export, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
