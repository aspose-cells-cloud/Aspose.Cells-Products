---
title:  Сохраните JSON как EMF, используя NodeJS.
description:  Использование Aspose.Cells Cloud SDK для NodeJS для сохранения файла формата JSON как файла формата EMF.
kwords: Excel, Save JSON as EMF, REST, NodeJS
howto: How to save JSON as EMF using Aspose.Cells Cloud NodeJS library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить JSON как EMF." h2="Библиотека NodeJS для сохранения JSON как EMF" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в NodeJS. Это профессиональное решение для сохранения JSON как EMF и других форматов документов онлайн с помощью NodeJS." urlsection="saveas/json-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл JSON как EMF в NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение формата файлов из JSON как EMF — сложная задача. Все переходы формата JSON в EMF выполняются нашим NodeJS SDK, сохраняя при этом основное структурное и логическое содержимое исходной таблицы JSON. Наша библиотека NodeJS — это профессиональное решение для сохранения файлов JSON в формате EMF онлайн. Этот Cloud SDK предоставляет разработчикам NodeJS мощные функциональные возможности и идеальный вывод EMF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода NodeJS для сохранения JSON как EMF с использованием REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.json",
      folder: "CellsTests",
      newfilename: "Book1Saveas.emf",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить JSON как EMF с помощью библиотеки Cloud NodeJS Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку NodeJS и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в JavaScript.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>узел v6.17.1 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
