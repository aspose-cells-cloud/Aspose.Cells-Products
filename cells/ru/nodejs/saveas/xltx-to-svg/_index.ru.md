---
title:  Сохраните XLTX как SVG с помощью NodeJS.
description:  Использование Aspose.Cells Cloud SDK для NodeJS для сохранения файла формата XLTX как файла формата SVG.
kwords: Excel, Save XLTX as SVG, REST, NodeJS
howto: How to save XLTX as SVG using Aspose.Cells Cloud NodeJS library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить XLTX как SVG" h2="Библиотека NodeJS для сохранения XLTX как SVG" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в NodeJS. Это профессиональное решение для сохранения XLTX как SVG и других форматов документов онлайн с помощью NodeJS." urlsection="saveas/xltx-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл XLTX как SVG в NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение формата файла XLTX как SVG — сложная задача. Все переходы формата XLTX в SVG выполняются нашим NodeJS SDK с сохранением основного структурного и логического содержимого исходной электронной таблицы XLTX. Наша библиотека NodeJS — это профессиональное решение для сохранения файлов XLTX в виде SVG онлайн. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и идеальный вывод SVG.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода NodeJS для сохранения XLTX как SVG с использованием REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xltx",
      folder: "CellsTests",
      newfilename: "Book1Saveas.svg",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить XLTX как SVG с помощью библиотеки Cloud NodeJS Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку NodeJS и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в JavaScript.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
