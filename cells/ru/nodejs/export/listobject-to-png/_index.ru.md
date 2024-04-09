---
title:  Экспортируйте LISTOBJECT в PNG из Excel с помощью Cloud SDK Cells для NodeJS.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспортировать LISTOBJECT в PNG из Excel" h2="Библиотека NodeJS для экспорта LISTOBJECT в файл PNG" p="Используйте «Экспорт API» из «Cells Cloud» для экспорта рабочих процессов внутренних объектов файлов Excel в NodeJS. Это профессиональное решение для экспорта LISTOBJECT в файл формата PNG из электронной таблицы онлайн с помощью NodeJS." urlsection="export/listobject-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект LISTOBJECT в файл формата PNG с помощью Cloud SDK Cells для NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта LISTOBJECT в файл PNG из файла Excel — сложная задача. Экспорт LISTOBJECT в переходы формата PNG выполняется нашим NodeJS SDK с сохранением основного структурного и логического содержимого исходной таблицы LISTOBJECT. Наша библиотека NodeJS — это профессиональное решение для онлайн-экспорта объектов LISTOBJECT в файлы формата PNG. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и идеальный вывод PNG.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода в NodeJS с использованием REST API для экспорта LISTOBJECT в формат PNG из электронной таблицы" gistPath="" %}}
  
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
      format: "png",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Node для экспорта объектов из Excel LISTOBJECT в PNG" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postExport` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
