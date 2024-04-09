---
title:  Преобразуйте HTML в PDF, используя C#.
description:  Использование Cloud SDK Aspose.Cells для C# для преобразования файла формата HTML в файл формата PDF.
kwords: Excel, Convert HTML to PDF, REST, C#
howto: How to convert HTML to PDF using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Преобразовать HTML в PDF" h2="C# библиотека для преобразования HTML в PDF" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Net. Это профессиональное решение для онлайн-конвертации HTML в PDF и других форматов документов с использованием C#." urlsection="conversion/html-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразуйте HTML в PDF с помощью Cloud SDK Cells для C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов с HTML в PDF может оказаться сложной задачей. Наш SDK C# обрабатывает все преобразования форматов HTML в PDF, сохраняя при этом основное структурное и логическое содержимое исходной таблицы HTML. Наша библиотека C# предоставляет профессиональное решение для онлайн-конвертации файлов HTML в PDF. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и обеспечивает высококачественный результат PDF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Пример кода для преобразования HTML в PDF с помощью Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.html";
    string format = "pdf";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.pdf";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как преобразовать HTML в PDF с помощью библиотеки Cloud Net Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку C# и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру C#.</li>
<li>Используйте метод `PutConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
