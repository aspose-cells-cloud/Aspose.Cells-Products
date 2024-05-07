---
title:  Конвертируйте TXT в PPTX с помощью Go
description: Использование Cloud SDK Aspose.Cells для Go для преобразования файла формата TXT в файл формата PPTX.
kwords: Excel, Convert TXT to PPTX, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert TXT to PPTX using the Cells Cloud Go library.","description": "How to convert TXT to PPTX using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/conversion/txt-to-pptx/","step": [{ "@type": "HowToStep","name": "How to convert TXT to PPTX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-pptx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert TXT to PPTX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-pptx/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert TXT to PPTX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-pptx/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to convert TXT to PPTX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-pptx/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать TXT в PPTX" h2="Библиотека Go для преобразования TXT в PPTX" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Go. Это профессиональное решение для конвертации TXT в PPTX и другие форматы документов онлайн с помощью Go." urlsection="conversion/txt-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразование TXT в PPTX с помощью Cloud SDK Cells для Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из TXT в PPTX может оказаться сложной задачей. Наш Go SDK обрабатывает все преобразования форматов TXT в PPTX, сохраняя при этом основное структурное и логическое содержимое исходной таблицы TXT. Наша библиотека Go предоставляет профессиональное решение для онлайн-конвертирования файлов TXT в PPTX. Этот Cloud SDK предоставляет разработчикам Go мощные функциональные возможности и обеспечивает высококачественный вывод PPTX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Go для преобразования TXT в PPTX с использованием Cloud SDK Cells" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.txt")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "pptx"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.pptx")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как конвертировать TXT в PPTX с помощью библиотеки Cloud Go Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Go и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в go.</li>
<li>Используйте метод `PutConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>версия go go1.13.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
