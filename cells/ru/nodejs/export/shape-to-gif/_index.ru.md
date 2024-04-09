---
title:  Экспортируйте SHAPE в GIF из Excel с помощью Cloud SDK Cells для NodeJS.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспортировать SHAPE в GIF из Excel" h2="Библиотека NodeJS для экспорта SHAPE в файл GIF." p="Используйте «Экспорт API» из «Cells Cloud» для экспорта рабочих процессов внутренних объектов файлов Excel в NodeJS. Это профессиональное решение для экспорта файла формата SHAPE в GIF из электронной таблицы онлайн с помощью NodeJS." urlsection="export/shape-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект SHAPE в файл формата GIF с помощью Cloud SDK Cells для NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта SHAPE в файл GIF из файла Excel — сложная задача. Экспорт переходов формата SHAPE в GIF выполняется нашим NodeJS SDK с сохранением основного структурного и логического содержимого исходной таблицы SHAPE. Наша библиотека NodeJS — это профессиональное решение для онлайн-экспорта объектов SHAPE в файлы формата GIF. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и идеальный вывод GIF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода в NodeJS с использованием REST API для экспорта SHAPE в формат GIF из электронной таблицы" gistPath="" %}}
  
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
      objectType : "shape",
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Node для экспорта объектов из Excel SHAPE в GIF" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postExport` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
