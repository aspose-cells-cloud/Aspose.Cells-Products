---
title:  Сохраните ЧИСЛА как EMF, используя C#.
description: Использование Aspose.Cells Cloud SDK для C# для сохранения файла формата NUMBERS как файла формата EMF.
kwords: Excel, Save NUMBERS as EMF, REST, C#
howto: How to save NUMBERS as EMF using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить ЦИФРЫ как EMF" h2="C# библиотека для сохранения ЧИСЕЛ как EMF" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Net. Это профессиональное решение для сохранения ЧИСЕЛ как EMF и других форматов документов онлайн с использованием C#." urlsection="saveas/numbers-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл NUMBERS как EMF в C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение формата файлов из NUMBERS как EMF — сложная задача. Все переходы формата NUMBERS в EMF выполняются нашим SDK C# с сохранением основного структурного и логического содержимого исходной таблицы NUMBERS. Наша библиотека C# — это профессиональное решение для сохранения ЧИСЕЛ в виде файлов EMF в Интернете. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и идеальный результат EMF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Пример кода для сохранения ЧИСЕЛ как EMF с использованием REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string newfilename = "Book1SaveAs.emf";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить ЧИСЛА как EMF, используя библиотеку Cloud Net Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку C# и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру C#.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
