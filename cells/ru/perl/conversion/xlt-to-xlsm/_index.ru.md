---
title:  Конвертируйте XLT в XLSM, используя Perl.
description:  Использование Cloud SDK Aspose.Cells для Perl для преобразования файла формата XLT в файл формата XLSM.
kwords: Excel, Convert XLT to XLSM, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLT to XLSM using the Cells Cloud Perl library.","description": "How to convert XLT to XLSM using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/conversion/xlt-to-xlsm/","step": [{ "@type": "HowToStep","name": "How to convert XLT to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlt-to-xlsm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLT to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlt-to-xlsm/","text": "Install Perl package and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLT to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlt-to-xlsm/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to convert XLT to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlt-to-xlsm/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать XLT в XLSM" h2="Perl библиотека для конвертации XLT в XLSM" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Perl. Это профессиональное решение для онлайн-конвертирования XLT в XLSM и другие форматы документов с помощью номера Perl." urlsection="conversion/xlt-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразуйте XLT в XLSM с помощью Cloud SDK Cells для Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLT в XLSM может оказаться сложной задачей. Наш SDK Perl обрабатывает все преобразования форматов XLT в XLSM, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы XLT. Наша библиотека Perl предоставляет профессиональное решение для онлайн-конвертирования файлов XLT в XLSM. Этот Cloud SDK предоставляет разработчикам Perl мощные функциональные возможности и обеспечивает высококачественный вывод XLSM.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Пример кода для преобразования XLT в XLSM с помощью Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xlsm";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xlt");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xlt") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xlsm") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как конвертировать XLT в XLSM с помощью библиотеки Cells Cloud Perl." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите пакет Perl и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Perl.</li>
<li>Используйте метод `put_convert_workbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
