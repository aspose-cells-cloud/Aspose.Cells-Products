---
title:  Сохраните ODS в формате GIF, используя номер Perl.
description:  Использование Aspose.Cells Cloud SDK для Perl для сохранения файла формата ODS в формате GIF.
kwords: Excel, Save ODS as GIF, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save ODS as GIF using the Cells Cloud Perl library.","description": "How to save ODS as GIF using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/saveas/ods-to-gif/","step": [{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/ods-to-gif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/ods-to-gif/","text": "Install Perl library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/ods-to-gif/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/ods-to-gif/","text": "Call post_workbook_save_as method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить ODS в формате GIF" h2="Perl библиотека для сохранения ODS в формате GIF" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Perl. Это профессиональное решение для сохранения ODS в формате GIF и других форматов документов в Интернете с помощью Perl." urlsection="saveas/ods-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл ODS в формате GIF по номеру Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из ODS в формате GIF — сложная задача. Все переходы формата ODS в GIF выполняются нашим SDK Perl с сохранением основного структурного и логического содержимого исходной электронной таблицы ODS. Наша библиотека Perl — это профессиональное решение для сохранения ODS в формате GIF в Интернете. Этот Cloud SDK предоставляет разработчикам Perl мощные функциональные возможности и идеальный вывод GIF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Пример кода для сохранения ODS в формате GIF с использованием REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.ods';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.gif';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как сохранить ODS в формате GIF с помощью библиотеки Cells Cloud Perl." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Perl и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Perl.</li>
<li>Позвонить_рабочая тетрадь_save_as для получения результирующего потока</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
