---
title:  Преобразование XLTX в FODS с помощью NodeJS
description:  Использование Cloud SDK Aspose.Cells для NodeJS для преобразования файла формата XLTX в файл формата FODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Конвертировать XLTX в FODS" h2="Библиотека NodeJS для преобразования XLTX в FODS" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах NodeJS. Это профессиональное решение для онлайн-конвертации XLTX в FODS и другие форматы документов с помощью NodeJS." urlsection="conversion/xltx-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразуйте XLTX в FODS с помощью Cloud SDK Cells для NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLTX в FODS может оказаться сложной задачей. Наш NodeJS SDK обрабатывает все преобразования формата XLTX в FODS, сохраняя при этом основное структурное и логическое содержимое исходной таблицы XLTX. Наша библиотека NodeJS предоставляет профессиональное решение для онлайн-конвертации файлов XLTX в FODS. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и обеспечивает высококачественный вывод FODS.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода NodeJS для преобразования XLTX в FODS с использованием Cloud SDK Cells" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xltx"),
        format: "fods",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Node для преобразования файлов Excel в другие форматы XLTX в FODS." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `putConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
