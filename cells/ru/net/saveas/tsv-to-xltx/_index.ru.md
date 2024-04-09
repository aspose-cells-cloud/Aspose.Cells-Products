---
title:  Сохраните TSV как XLTX, используя C#.
description:  Использование Aspose.Cells Cloud SDK для C# для сохранения файла формата TSV как файла формата XLTX.
kwords: Excel, Save TSV as XLTX, REST, C#
howto: How to save TSV as XLTX using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить TSV как XLTX" h2="C# библиотека для сохранения TSV как XLTX" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Net. Это профессиональное решение для сохранения TSV в формате XLTX и других форматов документов онлайн с использованием номера C#." urlsection="saveas/tsv-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл TSV как XLTX по номеру C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из TSV в формате XLTX — сложная задача. Все переходы формата TSV в XLTX выполняются нашим SDK C# с сохранением основного структурного и логического содержимого исходной таблицы TSV. Наша библиотека C# — это профессиональное решение для сохранения файлов TSV в формате XLTX онлайн. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и идеальный вывод XLTX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Пример кода для сохранения TSV как XLTX с использованием REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.tsv";
    string newfilename = "Book1SaveAs.xltx";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить TSV как XLTX, используя библиотеку Cloud Net Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку C# и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру C#.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
