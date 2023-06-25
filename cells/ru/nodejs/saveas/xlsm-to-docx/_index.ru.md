---
title:  Сохраните XLSM как DOCX API для NodeJS.
description: Использование Aspose.Cells Cloud SDK для NodeJS для сохранения файла формата XLSM в виде файла формата DOCX.
url: /ru/nodejs/saveas/xlsm-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API для сохранения XLSM как DOCX" h2="Библиотека NodeJS для сохранения XLSM в формате DOCX" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в NodeJS. Это профессиональное решение для сохранения XLSM в виде DOCX и других форматов документов в Интернете с использованием NodeJS." urlsection="saveas/xlsm-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл XLSM как DOCX в NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из XLSM в виде DOCX — сложная задача. Все переходы из формата XLSM в формат DOCX выполняются нашим NodeJS SDK с сохранением основного структурного и логического содержимого исходной электронной таблицы XLSM. Наша библиотека NodeJS — это профессиональное решение для сохранения XLSM в виде файлов DOCX в Интернете. Этот облачный SDK предоставляет разработчикам NodeJS мощные функциональные возможности и идеальный вывод DOCX.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в NodeJS с использованием REST API для сохранения XLSM в формате DOCX" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xlsm",
      folder: "CellsTests",
      newfilename: "Book1Saveas.docx",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Node API для сохранения XLSM в формате DOCX" >}}
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
