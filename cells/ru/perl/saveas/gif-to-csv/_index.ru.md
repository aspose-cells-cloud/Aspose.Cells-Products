﻿---
title:  Сохраните GIF как CSV, используя Perl.
description: Использование Aspose.Cells Cloud SDK для Perl для сохранения файла формата GIF в формате CSV.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Сохранить GIF как CSV" h2="Perl библиотека для сохранения GIF в формате CSV" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Perl. Это профессиональное решение для сохранения GIF в формате CSV и других форматов документов в Интернете с помощью Perl." urlsection="saveas/gif-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл GIF в формате CSV по номеру Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из GIF в CSV — сложная задача. Все переходы формата GIF в CSV выполняются нашим SDK Perl с сохранением основного структурного и логического содержимого исходной таблицы GIF. Наша библиотека Perl — это профессиональное решение для сохранения GIF в формате CSV в Интернете. Этот Cloud SDK предоставляет разработчикам Perl мощные функциональные возможности и идеальный вывод в формате CSV.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Пример кода для сохранения GIF в формате CSV с использованием REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.gif';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.csv';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cloud SDK Cells для Perl, чтобы сохранять файлы Excel в других форматах: GIF или CSV." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Позвонить_рабочая тетрадь_save_as для получения результирующего потока</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
