﻿---
title:  Сохраните XML как PPTX API для C#
description:  Облачные API и SDK для Microsoft Excel и OpenOffice Calc. Преобразование электронной таблицы в файл другого формата.
url: /ru/net/saveas/xml-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API для сохранения XML как PPTX" h2="C# библиотека для сохранения XML как PPTX" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Net. Это профессиональное решение для сохранения XML как PPTX и других форматов документов в Интернете с использованием C#." urlsection="saveas/xml-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл XML как PPTX в C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из XML в виде PPTX — сложная задача. Все переходы между форматами XML и PPTX выполняются нашим SDK C# с сохранением основного структурного и логического содержимого исходной электронной таблицы XML. Наша библиотека C# — это профессиональное решение для сохранения XML в виде файлов PPTX в Интернете. Этот облачный SDK предоставляет C# разработчикам мощную функциональность и идеальный вывод PPTX.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в C# с использованием REST API для сохранения XML в формате PPTX" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xml";
    string newfilename = "Book1SaveAs.pptx";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать C# API для сохранения XML в формате PPTX" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод CellsSaveAsPostDocumentSaveAs, чтобы получить результирующий поток.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Чистый стандарт 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}