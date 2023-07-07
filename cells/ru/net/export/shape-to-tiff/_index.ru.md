---
title:  Экспортируйте ФОРМУ в TIFF из электронной таблицы, используя C# API
description:  Aspose.Cells Cloud REST API поддерживает экспорт {0} в файлы формата {1} с использованием {2}.
url: /ru/net/export/shape-to-tiff/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API для экспорта SHAPE в файл TIFF" h2="C# библиотека для экспорта SHAPE в файл TIFF" p="Используйте Cells Export REST API для экспорта рабочих процессов внутренних объектов электронных таблиц в Net. Это профессиональное решение для экспорта файла формата SHAPE в файл формата TIFF из электронной таблицы онлайн с использованием C#." urlsection="export/shape-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспорт объекта SHAPE в файл формата TIFF в C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта SHAPE в файл TIFF из электронной таблицы является сложной задачей. Экспорт переходов SHAPE в формат TIFF выполняется нашим SDK C# при сохранении основного структурного и логического содержимого исходной электронной таблицы SHAPE. Наша библиотека C# — это профессиональное решение для онлайн-экспорта объектов SHAPE в файлы формата TIFF. Этот облачный SDK предоставляет C# разработчикам мощную функциональность и идеальный результат TIFF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в C# с использованием REST API для экспорта SHAPE в формат TIFF из электронной таблицы" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "tiff";
    string objectType ="shape";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать C# API для экспорта SHAPE в TIFF" >}}
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
