---
title:  Сохранить НОМЕРА как SXC API для Perl
description:  Использование Aspose.Cells Cloud SDK для Perl для сохранения файла формата NUMBERS в виде файла формата SXC.
url: /ru/perl/saveas/numbers-to-sxc/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API, чтобы сохранить НОМЕРА как SXC" h2="Библиотека Perl для сохранения NUMBERS как SXC" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Perl. Это профессиональное решение для сохранения NUMBERS в формате SXC и других форматах документов в Интернете с использованием Perl." urlsection="saveas/numbers-to-sxc/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл NUMBERS как SXC в Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из NUMBERS как SXC — сложная задача. Все преобразования формата NUMBERS в формат SXC выполняются с помощью нашего SDK Perl с сохранением основного структурного и логического содержимого исходной электронной таблицы NUMBERS. Наша библиотека Perl — это профессиональное решение для сохранения NUMBERS в виде файлов SXC в Интернете. Этот облачный SDK предоставляет Perl разработчикам мощную функциональность и отличный результат SXC.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Perl с использованием REST API для сохранения NUMBERS в формате SXC" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.numbers';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.sxc';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Perl API для сохранения NUMBERS как SXC" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызов ячеек_сохранять_как_почта_документ_сохранять_как метод получения результирующего потока</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
