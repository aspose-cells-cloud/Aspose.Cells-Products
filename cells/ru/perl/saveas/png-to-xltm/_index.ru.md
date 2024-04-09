---
title: Сохраните PNG как XLTM, используя Perl.
description:  Использование Aspose.Cells Cloud SDK для Perl для сохранения файла формата PNG как файла формата XLTM.
kwords: Excel, Save PNG as XLTM, REST, Perl
howto: How to save PNG as XLTM using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить PNG как XLTM" h2="Perl библиотека для сохранения PNG как XLTM" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Perl. Это профессиональное решение для сохранения PNG в формате XLTM и других форматов документов онлайн с использованием Perl." urlsection="saveas/png-to-xltm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл PNG как XLTM в Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение файлов формата PNG в формате XLTM — сложная задача. Все переходы формата PNG в XLTM выполняются нашим SDK Perl с сохранением основного структурного и логического содержимого исходной таблицы PNG. Наша библиотека Perl — это профессиональное решение для сохранения PNG в виде файлов XLTM в Интернете. Этот Cloud SDK предоставляет разработчикам Perl мощные функциональные возможности и отличный результат XLTM.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Пример кода для сохранения PNG как XLTM с использованием REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.png';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.xltm';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить PNG как XLTM, используя библиотеку Cells Cloud Perl." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Perl и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Perl.</li>
<li>Позвонить_рабочая тетрадь_save_as для получения результирующего потока</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
