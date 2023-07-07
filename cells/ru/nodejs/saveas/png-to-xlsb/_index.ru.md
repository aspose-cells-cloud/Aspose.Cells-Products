---
title:  Сохранить PNG как XLSB API для NodeJS
description:  Использование Aspose.Cells Cloud SDK для NodeJS для сохранения файла формата PNG в виде файла формата XLSB.
url: /ru/nodejs/saveas/png-to-xlsb/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API, чтобы сохранить PNG как XLSB" h2="Библиотека NodeJS для сохранения PNG как XLSB" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в NodeJS. Это профессиональное решение для сохранения PNG в формате XLSB и других форматах документов в Интернете с помощью NodeJS." urlsection="saveas/png-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл PNG как XLSB в NodeJS." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов с PNG как XLSB — сложная задача. Все переходы формата PNG в формат XLSB выполняются нашим NodeJS SDK при сохранении основного структурного и логического содержимого исходной электронной таблицы PNG. Наша библиотека NodeJS — это профессиональное решение для сохранения PNG в виде файлов XLSB в Интернете. Этот облачный SDK предоставляет разработчикам NodeJS мощную функциональность и идеальный вывод XLSB.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в NodeJS с использованием REST API для сохранения PNG в формате XLSB" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.png",
      folder: "CellsTests",
      newfilename: "Book1Saveas.xlsb",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать узел API для сохранения PNG в формате XLSB" >}}
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
