---
title:  Преобразуйте TXT в PDF с помощью NodeJS.
description:  Использование Cloud SDK Aspose.Cells для NodeJS для преобразования файла формата TXT в файл формата PDF.
kwords: Excel, Convert TXT to PDF, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert TXT to PDF using the Cells Cloud NodeJS library.","description": "How to convert TXT to PDF using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/conversion/txt-to-pdf/","step": [{ "@type": "HowToStep","name": "How to convert TXT to PDF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/txt-to-pdf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert TXT to PDF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/txt-to-pdf/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert TXT to PDF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/txt-to-pdf/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to convert TXT to PDF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/txt-to-pdf/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Преобразовать TXT в PDF" h2="Библиотека NodeJS для преобразования TXT в PDF" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах NodeJS. Это профессиональное решение для онлайн-конвертации TXT в PDF и другие форматы документов с помощью NodeJS." urlsection="conversion/txt-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразуйте TXT в PDF с помощью Cloud SDK Cells для NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из TXT в PDF может оказаться сложной задачей. Наш NodeJS SDK обрабатывает все преобразования форматов TXT в PDF, сохраняя при этом основное структурное и логическое содержимое исходной таблицы TXT. Наша библиотека NodeJS предоставляет профессиональное решение для онлайн-конвертации TXT в файлы PDF. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и обеспечивает высококачественный вывод PDF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода NodeJS для преобразования TXT в PDF с использованием Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.txt"),
        format: "pdf",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как преобразовать TXT в PDF с помощью облачной библиотеки NodeJS Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку NodeJS и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в JavaScript.</li>
<li>Используйте метод `putConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
