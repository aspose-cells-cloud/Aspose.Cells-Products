---
title:  Преобразуйте ЧИСЛА в XLS, используя C#.
description:  Использование Cloud SDK Aspose.Cells для C# для преобразования файла формата NUMBERS в файл формата XLS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Конвертировать ЧИСЛА в XLS" h2="C# библиотека для конвертации ЧИСЕЛ в XLS" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Net. Это профессиональное решение для конвертации ЧИСЕЛ в XLS и другие форматы документов онлайн с помощью C#." urlsection="conversion/numbers-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразуйте ЧИСЛА в XLS с помощью Cells Cloud SDK для C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из NUMBERS в XLS может оказаться сложной задачей. Наш SDK C# обрабатывает все преобразования формата NUMBERS в формат XLS, сохраняя при этом основное структурное и логическое содержимое исходной таблицы NUMBERS. Наша библиотека C# предоставляет профессиональное решение для онлайн-конвертации ЧИСЕЛ в файлы XLS. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и обеспечивает высококачественный вывод в формате XLS.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Пример кода для преобразования ЧИСЕЛ в XLS с помощью Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string format = "xls";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xls";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK for Net для преобразования файлов Excel в другие форматы NUMBERS в XLS." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `PutConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>NET Framework 4.5.2 или новее</li>
<li>Net Standard 2.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
