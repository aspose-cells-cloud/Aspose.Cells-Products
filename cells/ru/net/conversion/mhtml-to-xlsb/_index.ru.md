---
title:  Преобразуйте MHTML в XLSB, используя C#.
description:  Использование Cloud SDK Aspose.Cells для C# для преобразования файла формата MHTML в файл формата XLSB.
kwords: Excel, Convert MHTML to XLSB, REST, C#
howto: How to convert MHTML to XLSB using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать MHTML в XLSB" h2="C# библиотека для конвертации MHTML в XLSB" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Net. Это профессиональное решение для онлайн-конвертирования MHTML в XLSB и другие форматы документов с использованием номера C#." urlsection="conversion/mhtml-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразуйте MHTML в XLSB с помощью Cloud SDK Cells для C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из MHTML в XLSB может оказаться сложной задачей. Наш SDK C# обрабатывает все преобразования форматов MHTML в XLSB, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы MHTML. Наша библиотека C# предоставляет профессиональное решение для онлайн-конвертирования файлов MHTML в XLSB. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и обеспечивает высококачественный вывод XLSB.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Пример кода для преобразования MHTML в XLSB с помощью Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.mhtml";
    string format = "xlsb";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xlsb";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как преобразовать MHTML в XLSB с помощью библиотеки Cloud Net Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку C# и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру C#.</li>
<li>Используйте метод `PutConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
