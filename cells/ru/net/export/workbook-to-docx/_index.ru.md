﻿---
title:  Экспорт WORKBOOK в DOCX из электронной таблицы с помощью C# API
description: Aspose.Cells Облачный REST API поддерживает экспорт Excel файлов и внутренних объектов в различные форматы файлов. SDK поддерживает различные языки разработки. Среди них Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby и swift.
url: /ru/net/export/workbook-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API для экспорта WORKBOOK в файл DOCX" h2="C# библиотека для экспорта WORKBOOK в файл DOCX" p="Используйте Cells Export REST API для экспорта рабочих процессов внутренних объектов электронных таблиц в Net. Это профессиональное решение для экспорта файла формата WORKBOOK в DOCX из электронной таблицы онлайн с использованием C#." urlsection="export/workbook-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспорт объекта WORKBOOK в файл формата DOCX в C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта WORKBOOK в файл DOCX из электронной таблицы — сложная задача. Экспорт переходов WORKBOOK в формат DOCX выполняется нашим SDK C# при сохранении основного структурного и логического содержимого исходной электронной таблицы WORKBOOK. Наша библиотека C# — это профессиональное решение для онлайн-экспорта объектов WORKBOOK в файлы формата DOCX. Этот облачный SDK предоставляет C# разработчикам мощную функциональность и идеальный вывод в формате DOCX.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в C# с использованием REST API для экспорта WORKBOOK в формат DOCX из электронной таблицы" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "docx";
    string objectType ="workbook";
    LightCellsApi lightCellsApi =
        new LightCellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    IDictionary<string ,Stream> files = new  Dictionary<string ,Stream>();
    files.Add("Book1.xlsx" , File.OpenRead("Book1.xlsx"));
    files.Add("myDocument.xlsx", File.OpenRead("myDocument.xlsx"));
    var filesResult = lightCellsApi.PostExport(files, objectType, format);
    foreach (var file in filesResult.Files)
    {
        string v = file.FileContent;
        string filename = file.Filename;
        byte[] workbookData = System.Convert.FromBase64String(v);
        MemoryStream memoryStream = new MemoryStream(workbookData, 0, workbookData.Length);
        memoryStream.Seek(0, SeekOrigin.Begin);
        using (FileStream fileStream = File.Create( filename))
        {
            fileStream.Position = 0;
            memoryStream.CopyTo(fileStream);
            fileStream.Close();
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать C# API для экспорта WORKBOOK в DOCX" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод PostExport, чтобы получить результирующий поток</li>
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