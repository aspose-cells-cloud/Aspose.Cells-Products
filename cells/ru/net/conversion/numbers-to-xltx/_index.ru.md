---
title:  Преобразуйте ЧИСЛА в XLTX, используя C#.
description:  Использование Cloud SDK Aspose.Cells для C# для преобразования файла формата NUMBERS в файл формата XLTX.
kwords: Excel, Convert NUMBERS to XLTX, REST, C#
howto: How to convert NUMBERS to XLTX using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Преобразовать ЧИСЛА в XLTX" h2="C# библиотека для преобразования ЧИСЕЛ в XLTX" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Net. Это профессиональное решение для конвертации ЧИСЕЛ в XLTX и другие форматы документов онлайн с помощью C#." urlsection="conversion/numbers-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразуйте ЧИСЛА в XLTX с помощью Cells Cloud SDK для C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из NUMBERS в XLTX может оказаться сложной задачей. Наш SDK C# обрабатывает все преобразования форматов NUMBERS в XLTX, сохраняя при этом основное структурное и логическое содержимое исходной таблицы NUMBERS. Наша библиотека C# предоставляет профессиональное решение для онлайн-конвертации ЧИСЕЛ в файлы XLTX. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и обеспечивает высококачественный вывод XLTX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Пример кода для преобразования ЧИСЕЛ в XLTX с помощью Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string format = "xltx";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xltx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как преобразовать ЧИСЛА в XLTX с помощью библиотеки Cloud Net Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку C# и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру C#.</li>
<li>Используйте метод `PutConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
