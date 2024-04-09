---
title:  Экспортируйте WORKBOOK в HTML из Excel с помощью Cloud SDK Cells для C#.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспортировать РАБОЧУЮ КНИГУ на номер HTML из Excel." h2="Библиотека C# для экспорта WORKBOOK в файл HTML" p="Используйте «Экспорт API из Cells Cloud» для экспорта рабочих процессов внутренних объектов файлов Excel в Net. Это профессиональное решение для экспорта WORKBOOK в файл формата HTML из электронной таблицы онлайн с использованием C#." urlsection="export/workbook-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект WORKBOOK в файл формата HTML с помощью Cloud SDK Cells для C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта WORKBOOK в файл HTML из файла Excel — сложная задача. Экспорт WORKBOOK в формат переходов HTML выполняется нашим SDK C# с сохранением основного структурного и логического содержимого исходной таблицы WORKBOOK. Наша библиотека C# — это профессиональное решение для онлайн-экспорта объектов WORKBOOK в файлы формата HTML. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и идеальный результат HTML.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода в C# с использованием REST API для экспорта WORKBOOK в формат HTML из электронной таблицы" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "html";
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
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK for Net для экспорта объектов из Excel WORKBOOK в HTML" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postExport` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
