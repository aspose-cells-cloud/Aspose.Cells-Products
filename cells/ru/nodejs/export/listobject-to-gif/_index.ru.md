---
title: Экспортируйте LISTOBJECT в GIF из Excel с помощью Cloud SDK Cells для NodeJS.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords: Excel, listobject, gif, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Node to export objects from Excel LISTOBJECT to GIF","description": "How to use Cells Cloud SDK for Node to export objects from Excel LISTOBJECT to GIF","image": {"@type": "ImageObject"},"url": "/nodejs/export/listobject-to-gif/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel LISTOBJECT to GIF step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/listobject-to-gif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel LISTOBJECT to GIF step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/listobject-to-gif/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel LISTOBJECT to GIF step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/listobject-to-gif/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспорт LISTOBJECT в GIF из Excel" h2="Библиотека NodeJS для экспорта LISTOBJECT в файл GIF." p="Используйте «Экспорт API» из «Cells Cloud» для экспорта рабочих процессов внутренних объектов файлов Excel в NodeJS. Это профессиональное решение для экспорта LISTOBJECT в файл формата GIF из электронной таблицы онлайн с помощью NodeJS." urlsection="export/listobject-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект LISTOBJECT в файл формата GIF с помощью Cloud SDK Cells для NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта LISTOBJECT в файл GIF из файла Excel — сложная задача. Экспорт переходов формата LISTOBJECT в GIF выполняется нашим NodeJS SDK с сохранением основного структурного и логического содержимого исходной таблицы LISTOBJECT. Наша библиотека NodeJS — это профессиональное решение для онлайн-экспорта объектов LISTOBJECT в файлы формата GIF. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и идеальный вывод GIF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода в NodeJS с использованием REST API для экспорта LISTOBJECT в формат GIF из электронной таблицы" gistPath="" %}}
  
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
      objectType : "listobject",
      format: "gif",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Node для экспорта объектов из Excel LISTOBJECT в GIF." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postExport` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
