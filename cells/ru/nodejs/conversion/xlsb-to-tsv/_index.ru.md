﻿---
title:  Преобразование XLSB в TSV API для NodeJS
description:  Облачные API и SDK для Microsoft Excel и OpenOffice Calc. Преобразование электронной таблицы в файл другого формата.
url: /ru/nodejs/conversion/xlsb-to-tsv/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API для преобразования XLSB в TSV" h2="Библиотека NodeJS для преобразования XLSB в TSV" p="Используйте Cells Conversion REST API для создания настраиваемых рабочих процессов электронных таблиц в NodeJS. Это профессиональное решение для онлайн-конвертации XLSB в TSV и другие форматы документов с использованием NodeJS." urlsection="conversion/xlsb-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла XLSB в TSV в NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLSB в TSV — сложная задача. Все переходы между форматами XLSB и TSV выполняются нашим NodeJS SDK с сохранением основного структурного и логического содержимого исходной электронной таблицы XLSB. Наша библиотека NodeJS — это профессиональное решение для онлайн-конвертации файлов XLSB в TSV. Этот облачный SDK предоставляет разработчикам NodeJS мощную функциональность и идеальный вывод TSV.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в NodeJS с использованием REST API для преобразования XLSB в формат TSV" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xlsb"),
        format: "tsv",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Node API для преобразования XLSB в TSV" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод CellsWorkbookPutConvertWorkbook, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}