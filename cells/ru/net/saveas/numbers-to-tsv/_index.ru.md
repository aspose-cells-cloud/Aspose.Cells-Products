---
title:  Сохраните ЧИСЛА как TSV, используя C#.
description:  Использование Aspose.Cells Cloud SDK для C# для сохранения файла формата NUMBERS как файла формата TSV.
kwords: Excel, Save NUMBERS as TSV, REST, C#
howto: How to save NUMBERS as TSV using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить ЧИСЛА как TSV" h2="C# библиотека для сохранения ЧИСЕЛ в формате TSV" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Net. Это профессиональное решение для сохранения ЧИСЕЛ в формате TSV и других форматов документов онлайн с использованием C#." urlsection="saveas/numbers-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл NUMBERS как TSV в C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из NUMBERS в формате TSV — сложная задача. Все переходы формата NUMBERS в TSV выполняются нашим SDK C# с сохранением основного структурного и логического содержимого исходной таблицы NUMBERS. Наша библиотека C# — это профессиональное решение для сохранения ЧИСЕЛ в виде файлов TSV в Интернете. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и идеальный вывод TSV.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Пример кода для сохранения ЧИСЕЛ как TSV с использованием REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string newfilename = "Book1SaveAs.tsv";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить ЧИСЛА в формате TSV, используя библиотеку Cloud Net Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку C# и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру C#.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
