---
title:  Конвертируйте XLSB в TSV, используя C#.
description:  Использование Cloud SDK Aspose.Cells для C# для преобразования файла формата XLSB в файл формата TSV.
kwords: Excel, Convert XLSB to TSV, REST, C#
howto: How to convert XLSB to TSV using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать XLSB в TSV" h2="C# библиотека для конвертации XLSB в TSV" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Net. Это профессиональное решение для онлайн-конвертирования XLSB в TSV и другие форматы документов с использованием номера C#." urlsection="conversion/xlsb-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразуйте XLSB в TSV с помощью Cloud SDK Cells для C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLSB в TSV может оказаться сложной задачей. Наш SDK C# обрабатывает все преобразования формата XLSB в TSV, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы XLSB. Наша библиотека C# предоставляет профессиональное решение для онлайн-конвертирования файлов XLSB в TSV. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и обеспечивает высококачественный вывод TSV.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Пример кода для преобразования XLSB в TSV с помощью Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsb";
    string format = "tsv";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.tsv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как преобразовать XLSB в TSV с помощью библиотеки Cloud Net Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку C# и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру C#.</li>
<li>Используйте метод `PutConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
