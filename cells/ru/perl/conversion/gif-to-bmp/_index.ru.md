---
title:  Конвертируйте GIF в BMP, используя Perl.
description:  Использование Cloud SDK Aspose.Cells для Perl для преобразования файла формата GIF в файл формата BMP.
kwords: Excel, Convert GIF to BMP, REST, Perl
howto: How to convert GIF to BMP using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать GIF в BMP" h2="Perl библиотека для конвертации GIF в BMP" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Perl. Это профессиональное решение для конвертации GIF в BMP и другие форматы документов онлайн с помощью Perl." urlsection="conversion/gif-to-bmp/" >}}

{{< blocks/products/cells/cells-cloud-section title="Конвертируйте GIF в BMP с помощью Cloud SDK Cells для Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из GIF в BMP может оказаться сложной задачей. Наш SDK Perl обрабатывает все преобразования форматов GIF в BMP, сохраняя при этом основное структурное и логическое содержимое исходной таблицы GIF. Наша библиотека Perl предоставляет профессиональное решение для онлайн-конвертации GIF в файлы BMP. Этот Cloud SDK предоставляет разработчикам Perl мощные функциональные возможности и обеспечивает высококачественный результат BMP.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Пример кода для преобразования GIF в BMP с использованием Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "bmp";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.gif");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.gif") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.bmp") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как конвертировать GIF в BMP с помощью библиотеки Cells Cloud Perl." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите пакет Perl и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Perl.</li>
<li>Используйте метод `put_convert_workbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
