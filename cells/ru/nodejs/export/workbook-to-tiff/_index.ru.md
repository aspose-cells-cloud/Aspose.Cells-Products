---
title:  Экспортируйте WORKBOOK в TIFF из Excel с помощью Cells Cloud SDK для NodeJS.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords: Excel, workbook, tiff, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to TIFF","description": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to TIFF","image": {"@type": "ImageObject"},"url": "/nodejs/export/workbook-to-tiff/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to TIFF step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-tiff/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to TIFF step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-tiff/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to TIFF step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-tiff/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспортировать РАБОЧУЮ КНИГУ на номер TIFF из Excel." h2="Библиотека NodeJS для экспорта WORKBOOK в файл TIFF" p="Используйте «Экспорт API» из «Cells Cloud» для экспорта рабочих процессов внутренних объектов файлов Excel в NodeJS. Это профессиональное решение для экспорта WORKBOOK в файл формата TIFF из электронной таблицы онлайн с помощью NodeJS." urlsection="export/workbook-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект WORKBOOK в файл формата TIFF с помощью Cloud SDK Cells для NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта WORKBOOK в файл TIFF из файла Excel — сложная задача. Экспорт WORKBOOK в формат переходов TIFF выполняется нашим NodeJS SDK с сохранением основного структурного и логического содержимого исходной таблицы WORKBOOK. Наша библиотека NodeJS — это профессиональное решение для экспорта объектов WORKBOOK в файлы формата TIFF онлайн. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и идеальный вывод TIFF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода в NodeJS с использованием REST API для экспорта WORKBOOK в формат TIFF из электронной таблицы" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { LightCellsApi, PostExportRequest } = require("asposecellscloud");
    const localPath = "C:/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new LightCellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    const AssemblyTestXlsx = "assemblytest.xlsx";
    var dataAssemblyTestXlsx =fs.createReadStream(localPath  + AssemblyTestXlsx);
    const DataSourceXlsx = "datasource.xlsx";
    var dataDataSourceXlsx =fs.createReadStream(localPath  + DataSourceXlsx);
    var req = new PostExportRequest({
      file:{AssemblyTestXlsx:dataAssemblyTestXlsx ,DataSourceXlsx:dataDataSourceXlsx },
      objectType : "workbook",
      format: "tiff",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Node для экспорта объектов из Excel WORKBOOK в TIFF" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postExport` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
