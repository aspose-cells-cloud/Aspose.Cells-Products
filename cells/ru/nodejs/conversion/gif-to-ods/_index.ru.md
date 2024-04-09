---
title: Конвертируйте GIF в ODS с помощью NodeJS
description:  Использование Cloud SDK Aspose.Cells для NodeJS для преобразования файла формата GIF в файл формата ODS.
kwords: Excel, Convert GIF to ODS, REST, NodeJS
howto: How to convert GIF to ODS using Aspose.Cells Cloud NodeJS library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать GIF в ODS" h2="Библиотека NodeJS для преобразования GIF в ODS" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах NodeJS. Это профессиональное решение для конвертации GIF в ODS и другие форматы документов онлайн с помощью NodeJS." urlsection="conversion/gif-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Конвертируйте GIF в ODS с помощью Cloud SDK Cells для NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из GIF в ODS может оказаться сложной задачей. Наш NodeJS SDK обрабатывает все преобразования форматов GIF в ODS, сохраняя при этом основное структурное и логическое содержимое исходной таблицы GIF. Наша библиотека NodeJS предоставляет профессиональное решение для онлайн-конвертации GIF в файлы ODS. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и обеспечивает высококачественный вывод ODS.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода NodeJS для преобразования GIF в ODS с использованием Cloud SDK Cells" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.gif"),
        format: "ods",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как конвертировать GIF в ODS с помощью библиотеки Cloud NodeJS Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку NodeJS и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в JavaScript.</li>
<li>Используйте метод `putConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
