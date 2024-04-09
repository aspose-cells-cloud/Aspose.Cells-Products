---
title:  Сохраните CSV как PPTX с помощью NodeJS.
description:  Использование Aspose.Cells Cloud SDK для NodeJS для сохранения файла формата CSV как файла формата PPTX.
kwords: Excel, Save CSV as PPTX, REST, NodeJS
howto: How to save CSV as PPTX using Aspose.Cells Cloud NodeJS library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить CSV как PPTX" h2="Библиотека NodeJS для сохранения CSV как PPTX" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в NodeJS. Это профессиональное решение для сохранения CSV в формате PPTX и других форматов документов онлайн с помощью NodeJS." urlsection="saveas/csv-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл CSV как PPTX в NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из CSV в формате PPTX — сложная задача. Все переходы формата CSV в PPTX выполняются нашим NodeJS SDK с сохранением основного структурного и логического содержимого исходной таблицы CSV. Наша библиотека NodeJS — это профессиональное решение для сохранения файлов CSV в формате PPTX онлайн. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и идеальный вывод PPTX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода NodeJS для сохранения CSV как PPTX с использованием REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.csv",
      folder: "CellsTests",
      newfilename: "Book1Saveas.pptx",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить CSV в формате PPTX с помощью библиотеки Cloud NodeJS Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку NodeJS и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в JavaScript.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
