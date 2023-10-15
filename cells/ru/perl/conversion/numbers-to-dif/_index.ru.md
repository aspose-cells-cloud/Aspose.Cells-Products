---
title:  Преобразуйте ЧИСЛА в DIF, используя Perl.
description: Использование Cloud SDK Aspose.Cells для Perl для преобразования файла формата NUMBERS в файл формата DIF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Преобразовать ЧИСЛА в РАЗН" h2="Perl библиотека для преобразования ЧИСЕЛ в DIF" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Perl. Это профессиональное решение для онлайн-конвертации ЧИСЕЛ в DIF и другие форматы документов с помощью Perl." urlsection="conversion/numbers-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразуйте ЧИСЛА в DIF с помощью Cells Cloud SDK для Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из ЧИСЛОВ в DIF может оказаться сложной задачей. Наш SDK Perl обрабатывает все преобразования формата NUMBERS в DIF, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы NUMBERS. Наша библиотека Perl предоставляет профессиональное решение для онлайн-конвертирования ЧИСЕЛ в файлы DIF. Этот Cloud SDK предоставляет разработчикам Perl мощные функциональные возможности и обеспечивает высококачественный вывод в формате DIF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Пример кода для преобразования ЧИСЕЛ в DIF с помощью Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "dif";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.numbers");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.numbers") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.dif") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Perl SDK для преобразования ЧИСЕЛ в DIF" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `put_convert_workbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
