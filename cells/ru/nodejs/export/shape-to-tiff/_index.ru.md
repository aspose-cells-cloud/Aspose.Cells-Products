﻿---
title:  Экспорт SHAPE в TIFF из электронной таблицы с использованием NodeJS API
description: Aspose.Cells Облачный REST API поддерживает экспорт Excel файлов и внутренних объектов в различные форматы файлов. SDK поддерживает различные языки разработки. Среди них Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby и swift.
url: /ru/nodejs/export/shape-to-tiff/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API для экспорта SHAPE в файл TIFF" h2="Библиотека NodeJS для экспорта SHAPE в файл TIFF" p="Используйте Cells Export REST API для экспорта рабочих процессов внутренних объектов электронных таблиц в NodeJS. Это профессиональное решение для экспорта файла формата SHAPE в файл формата TIFF из электронной таблицы онлайн с использованием NodeJS." urlsection="export/shape-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспорт объекта SHAPE в файл формата TIFF в NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта SHAPE в файл TIFF из электронной таблицы является сложной задачей. Экспорт переходов SHAPE в формат TIFF выполняется нашим NodeJS SDK, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы SHAPE. Наша библиотека NodeJS — это профессиональное решение для экспорта объектов SHAPE в файлы формата TIFF онлайн. Этот облачный SDK предоставляет разработчикам NodeJS мощную функциональность и идеальный результат TIFF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в NodeJS с использованием REST API для экспорта SHAPE в формат TIFF из электронной таблицы" gistPath="" %}}
  
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
      format: "tiff",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Node API для экспорта SHAPE в TIFF" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод postExport, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}