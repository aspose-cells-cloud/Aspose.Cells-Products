﻿---
title:  Сохраните XLTM как MD API для NodeJS.
description:  Облачные API и SDK для Microsoft Excel и OpenOffice Calc. Преобразование электронной таблицы в файл другого формата.
url: /ru/nodejs/saveas/xltm-to-md/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API для сохранения XLTM как MD" h2="Библиотека NodeJS для сохранения XLTM как MD" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в NodeJS. Это профессиональное решение для сохранения XLTM как MD и других форматов документов онлайн с использованием NodeJS." urlsection="saveas/xltm-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл XLTM как MD в NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из XLTM в виде MD — сложная задача. Все переходы от формата XLTM к формату MD выполняются нашим NodeJS SDK при сохранении основного структурного и логического содержимого исходной электронной таблицы XLTM. Наша библиотека NodeJS — это профессиональное решение для сохранения XLTM в виде файлов MD в Интернете. Этот облачный SDK предоставляет разработчикам NodeJS мощную функциональность и идеальный вывод MD.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в NodeJS с использованием REST API для сохранения XLTM в формате MD" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xltm",
      folder: "CellsTests",
      newfilename: "Book1Saveas.md",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Node API для сохранения XLTM как MD" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод cellSaveAsPostDocumentSaveAs, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}