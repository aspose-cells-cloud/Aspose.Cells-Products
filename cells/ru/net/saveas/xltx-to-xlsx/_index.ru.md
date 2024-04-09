---
title:  Сохраните XLTX как XLSX, используя C#.
description:  Использование Aspose.Cells Cloud SDK для C# для сохранения файла формата XLTX как файла формата XLSX.
kwords: Excel, Save XLTX as XLSX, REST, C#
howto: How to save XLTX as XLSX using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить XLTX как XLSX" h2="C# библиотека для сохранения XLTX как XLSX" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Net. Это профессиональное решение для сохранения XLTX в формате XLSX и других форматов документов онлайн с использованием номера C#." urlsection="saveas/xltx-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл XLTX как XLSX по номеру C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из XLTX в XLSX — сложная задача. Все переходы формата XLTX в XLSX выполняются нашим SDK C# с сохранением основного структурного и логического содержимого исходной таблицы XLTX. Наша библиотека C# — это профессиональное решение для сохранения файлов XLTX в формате XLSX онлайн. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и идеальный вывод в формате XLSX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Пример кода для сохранения XLTX как XLSX с использованием REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xltx";
    string newfilename = "Book1SaveAs.xlsx";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить XLTX как XLSX, используя библиотеку Cloud Net Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку C# и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру C#.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
