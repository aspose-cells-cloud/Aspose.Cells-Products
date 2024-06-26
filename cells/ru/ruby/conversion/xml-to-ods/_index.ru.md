---
title:  Преобразование XML в ODS с помощью Ruby
description:  Использование Cloud SDK Aspose.Cells для Ruby для преобразования файла формата XML в файл формата ODS.
kwords: Excel, Convert XML to ODS, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XML to ODS using the Cells Cloud Ruby library.","description": "How to convert XML to ODS using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/conversion/xml-to-ods/","step": [{ "@type": "HowToStep","name": "How to convert XML to ODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/xml-to-ods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XML to ODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/xml-to-ods/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XML to ODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/xml-to-ods/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to convert XML to ODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/xml-to-ods/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать XML в ODS" h2="Библиотека Ruby для преобразования XML в ODS" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Ruby. Это профессиональное решение для онлайн-конвертирования XML в ODS и другие форматы документов с помощью Ruby." urlsection="conversion/xml-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразование XML в ODS с помощью Cloud SDK Cells для Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XML в ODS может оказаться сложной задачей. Наш Ruby SDK обрабатывает все преобразования форматов XML в ODS, сохраняя при этом основное структурное и логическое содержимое исходной таблицы XML. Наша библиотека Ruby предоставляет профессиональное решение для онлайн-преобразования XML в файлы ODS. Этот Cloud SDK предоставляет разработчикам Ruby мощные функциональные возможности и обеспечивает высококачественный вывод ODS.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Ruby для преобразования XML в ODS с использованием Cloud SDK Cells" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xml"
            format = 'ods'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как преобразовать XML в ODS с помощью библиотеки Cloud Ruby Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Ruby и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в Ruby.</li>
<li>Используйте метод `put_convert_workbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>рубин 2.5 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
