---
title:  Сохраните PNG как SXC с помощью Go.
description:  Использование Aspose.Cells Cloud SDK для Go для сохранения файла формата PNG как файла формата SXC.
kwords: Excel, Save PNG as SXC, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save PNG as SXC using the Cells Cloud Go library.","description": "How to save PNG as SXC using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/png-to-sxc/","step": [{ "@type": "HowToStep","name": "How to save PNG as SXC using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/png-to-sxc/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save PNG as SXC using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/png-to-sxc/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save PNG as SXC using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/png-to-sxc/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save PNG as SXC using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/png-to-sxc/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить PNG как SXC" h2="Библиотека Go для сохранения PNG как SXC" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Go. Это профессиональное решение для сохранения PNG в формате SXC и других форматов документов онлайн с помощью Go." urlsection="saveas/png-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл PNG как SXC в Go." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение файлов формата PNG как SXC — сложная задача. Все переходы формата PNG в SXC выполняются нашим Go SDK с сохранением основного структурного и логического содержимого исходной таблицы PNG. Наша библиотека Go — это профессиональное решение для сохранения PNG в формате SXC в Интернете. Этот Cloud SDK предоставляет разработчикам Go мощные функциональные возможности и идеальный вывод SXC.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Go для сохранения PNG как SXC с использованием REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.png"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.sxc"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как сохранить PNG как SXC с помощью библиотеки Cloud Go Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Go и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в go.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>версия go go1.13.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
