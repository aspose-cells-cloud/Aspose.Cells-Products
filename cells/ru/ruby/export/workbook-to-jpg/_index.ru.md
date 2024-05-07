---
title:  Экспортируйте WORKBOOK в JPG из Excel с помощью Cloud SDK Cells для Ruby.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords: Excel, workbook, jpg, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to JPG","description": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to JPG","image": {"@type": "ImageObject"},"url": "/ruby/export/workbook-to-jpg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to JPG step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/workbook-to-jpg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to JPG step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/workbook-to-jpg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKBOOK to JPG step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/workbook-to-jpg/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспорт WORKBOOK в JPG из Excel" h2="Библиотека Ruby для экспорта WORKBOOK в файл JPG." p="Используйте команду «Экспорт API из облака Cells» для экспорта рабочих процессов внутренних объектов файлов Excel в Ruby. Это профессиональное решение для экспорта WORKBOOK в файл формата JPG из электронной таблицы онлайн с помощью Ruby." urlsection="export/workbook-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект WORKBOOK в файл формата JPG с помощью Cloud SDK Cells для Ruby." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта WORKBOOK в файл JPG из файла Excel — сложная задача. Экспорт переходов формата WORKBOOK в JPG выполняется нашим Ruby SDK с сохранением основного структурного и логического содержимого исходной таблицы WORKBOOK. Наша библиотека Ruby — это профессиональное решение для онлайн-экспорта объектов WORKBOOK в файлы формата JPG. Этот Cloud SDK предоставляет разработчикам Ruby мощные функциональные возможности и идеальный вывод в формате JPG.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода на Ruby с использованием REST API для экспорта WORKBOOK в формат JPG из электронной таблицы" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::LiteCellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            files = {}      
            name = $DataSourceXlsx
            files[name] = ::File.open(File.expand_path("data/"+name),"r") 
            name =$AssemblyTestXlsx 
            files[name] = ::File.open(File.expand_path("data/"+name),"r")
            format = 'jpg'
            objectType =  'workbook'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cloud SDK Cells для Ruby для экспорта объектов из Excel WORKBOOK в JPG." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Вызовите метод post_export, чтобы получить результирующий поток.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>рубин 2.5 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
