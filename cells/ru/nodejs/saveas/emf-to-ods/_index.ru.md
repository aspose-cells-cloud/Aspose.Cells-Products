﻿---
title:  Сохранить EMF как ODS API для NodeJS
description:  Облачные API и SDK для Microsoft Excel и OpenOffice Calc. Преобразование электронной таблицы в файл другого формата.
url: /ru/nodejs/saveas/emf-to-ods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API для сохранения EMF как ODS" h2="Библиотека NodeJS для сохранения EMF как ODS" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в NodeJS. Это профессиональное решение для сохранения EMF в виде ODS и других форматов документов в Интернете с использованием NodeJS." urlsection="saveas/emf-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл EMF как ODS в NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов с EMF в виде ODS является сложной задачей. Все переходы EMF в формат ODS выполняются нашим NodeJS SDK при сохранении основного структурного и логического содержимого исходной электронной таблицы EMF. Наша библиотека NodeJS — это профессиональное решение для сохранения EMF в виде файлов ODS в Интернете. Этот облачный SDK предоставляет разработчикам NodeJS мощную функциональность и идеальный вывод ODS.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в NodeJS с использованием REST API для сохранения EMF в формате ODS" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.emf",
      folder: "CellsTests",
      newfilename: "Book1Saveas.ods",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать узел API для сохранения EMF в качестве ODS" >}}
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