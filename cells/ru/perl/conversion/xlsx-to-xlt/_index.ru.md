---
title:  Преобразование XLSX в XLT API для Perl
description: Использование Aspose.Cells Cloud SDK для Perl для преобразования файла формата XLSX в файл формата XLT.
url: /ru/perl/conversion/xlsx-to-xlt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API для преобразования XLSX в XLT" h2="Perl библиотека для преобразования XLSX в XLT" p="Используйте Cells Преобразование REST API для создания настраиваемых рабочих процессов электронных таблиц в Perl. Это профессиональное решение для преобразования XLSX в XLT и другие форматы документов онлайн с использованием Perl." urlsection="conversion/xlsx-to-xlt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла XLSX в XLT в Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLSX в XLT — сложная задача. Все переходы между форматами XLSX и XLT выполняются нашим SDK Perl с сохранением основного структурного и логического содержимого исходной электронной таблицы XLSX. Наша библиотека Perl — это профессиональное решение для онлайн-конвертации файлов XLSX в XLT. Этот облачный SDK предоставляет Perl разработчикам мощные функциональные возможности и превосходный результат в формате XLT.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Perl с использованием REST API для преобразования XLSX в формат XLT" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xlt";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xlsx");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xlsx") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xlt") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Perl API для преобразования XLSX в XLT" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызов ячеек_рабочая тетрадь_помещать_конвертировать_метод рабочей книги для получения результирующего потока</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
