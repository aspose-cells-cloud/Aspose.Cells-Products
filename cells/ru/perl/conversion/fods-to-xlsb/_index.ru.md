---
title:  Конвертируйте FODS в XLSB с помощью Perl.
description:  Использование Cloud SDK Aspose.Cells для Perl для преобразования файла формата FODS в файл формата XLSB.
kwords: Excel, Convert FODS to XLSB, REST, Perl
howto: How to convert FODS to XLSB using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать FODS в XLSB" h2="Perl библиотека для конвертации FODS в XLSB" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Perl. Это профессиональное решение для онлайн-конвертирования FODS в XLSB и другие форматы документов с использованием номера Perl." urlsection="conversion/fods-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразуйте FODS в XLSB с помощью Cloud SDK Cells для Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из FODS в XLSB может оказаться сложной задачей. Наш SDK Perl обрабатывает все преобразования формата FODS в XLSB, сохраняя при этом основное структурное и логическое содержимое исходной таблицы FODS. Наша библиотека Perl предоставляет профессиональное решение для онлайн-конвертирования файлов FODS в файлы XLSB. Этот Cloud SDK предоставляет разработчикам Perl мощные функциональные возможности и обеспечивает высококачественный вывод XLSB.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Пример кода для преобразования FODS в XLSB с помощью Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xlsb";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.fods");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.fods") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xlsb") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как конвертировать FODS в XLSB с помощью библиотеки Cells Cloud Perl." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите пакет Perl и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Perl.</li>
<li>Используйте метод `put_convert_workbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
