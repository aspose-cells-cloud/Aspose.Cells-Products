---
title:  Сохраните SXC как SQL, используя C#.
description:  Использование Aspose.Cells Cloud SDK для C# для сохранения файла формата SXC как файла формата SQL.
kwords: Excel, Save SXC as SQL, REST, C#
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save SXC as SQL using the Cells Cloud Net library.","description": "How to save SXC as SQL using the Cells Cloud Net library.","image": {"@type": "ImageObject"},"url": "/net/saveas/sxc-to-sql/","step": [{ "@type": "HowToStep","name": "How to save SXC as SQL using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/sxc-to-sql/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save SXC as SQL using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/sxc-to-sql/","text": "Install C# library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save SXC as SQL using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/sxc-to-sql/","text": "Open the source file in C#",},{ "@type": "HowToStep","name": "How to save SXC as SQL using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/sxc-to-sql/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить SXC как SQL" h2="C# библиотека для сохранения SXC как SQL" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Net. Это профессиональное решение для сохранения SXC в формате SQL и других форматов документов онлайн с использованием номера C#." urlsection="saveas/sxc-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл SXC как SQL в C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из SXC как SQL — сложная задача. Все переходы формата SXC в SQL выполняются нашим SDK C# с сохранением основного структурного и логического содержимого исходной электронной таблицы SXC. Наша библиотека C# — это профессиональное решение для сохранения SXC в виде файлов SQL в Интернете. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и идеальный вывод SQL.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Пример кода для сохранения SXC как SQL с использованием REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.sxc";
    string newfilename = "Book1SaveAs.sql";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как сохранить SXC как SQL с помощью библиотеки Cloud Net Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку C# и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру C#.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
