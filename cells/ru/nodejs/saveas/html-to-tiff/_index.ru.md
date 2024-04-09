---
title:  Сохраните HTML как TIFF с помощью NodeJS.
description:  Использование Aspose.Cells Cloud SDK для NodeJS для сохранения файла формата HTML как файла формата TIFF.
kwords: Excel, Save HTML as TIFF, REST, NodeJS
howto: How to save HTML as TIFF using Aspose.Cells Cloud NodeJS library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить HTML как TIFF" h2="Библиотека NodeJS для сохранения HTML как TIFF" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в NodeJS. Это профессиональное решение для сохранения HTML как TIFF и других форматов документов онлайн с помощью NodeJS." urlsection="saveas/html-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл HTML как TIFF в NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов с HTML как TIFF — сложная задача. Все переходы форматов с HTML на TIFF выполняются нашим NodeJS SDK с сохранением основного структурного и логического содержимого исходной таблицы HTML. Наша библиотека NodeJS — это профессиональное решение для сохранения файлов HTML как TIFF в Интернете. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и идеальный результат TIFF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода NodeJS для сохранения HTML как TIFF с использованием REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.html",
      folder: "CellsTests",
      newfilename: "Book1Saveas.tiff",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить HTML как TIFF с помощью библиотеки Cloud NodeJS Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку NodeJS и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в JavaScript.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
