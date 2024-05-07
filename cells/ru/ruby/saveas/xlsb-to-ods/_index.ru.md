---
title:  Сохраните XLSB как ODS, используя Ruby.
description:  Использование Cloud SDK Aspose.Cells для Ruby для сохранения файла формата XLSB как файла формата ODS.
kwords: Excel, Save XLSB as ODS, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSB as ODS using the Cells Cloud Ruby library.","description": "How to save XLSB as ODS using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/xlsb-to-ods/","step": [{ "@type": "HowToStep","name": "How to save XLSB as ODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlsb-to-ods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSB as ODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlsb-to-ods/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSB as ODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlsb-to-ods/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save XLSB as ODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlsb-to-ods/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить XLSB как ODS" h2="Библиотека Ruby для сохранения XLSB как ODS" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Ruby. Это профессиональное решение для сохранения XLSB в формате ODS и других форматов документов онлайн с использованием Ruby." urlsection="saveas/xlsb-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл XLSB как ODS в Ruby." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из XLSB в формате ODS — сложная задача. Все переходы формата XLSB в ODS выполняются нашим Ruby SDK с сохранением основного структурного и логического содержимого исходной электронной таблицы XLSB. Наша библиотека Ruby — это профессиональное решение для сохранения файлов XLSB в формате ODS онлайн. Этот Cloud SDK предоставляет разработчикам Ruby мощные функциональные возможности и идеальный результат ODS.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Ruby для сохранения XLSB как ODS с использованием REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.xlsb'
    save_options = nil
    newfilename = 'Book1Saveas.ods'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как сохранить XLSB как ODS с помощью библиотеки Cloud Ruby Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Ruby и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в Ruby.</li>
<li>Используйте метод `post_workbook_save_as` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>рубин 2.5 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
