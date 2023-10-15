---
title:  Конвертируйте XLS в TSV, используя C#.
description:  Использование Cloud SDK Aspose.Cells для C# для преобразования файла формата XLS в файл формата TSV.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Конвертировать XLS в TSV" h2="C# библиотека для конвертации XLS в TSV" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Net. Это профессиональное решение для онлайн-конвертации XLS в TSV и другие форматы документов с использованием номера C#." urlsection="conversion/xls-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразуйте XLS в TSV с помощью Cloud SDK Cells для C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLS в TSV может оказаться сложной задачей. Наш SDK C# обрабатывает все преобразования форматов XLS в TSV, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы XLS. Наша библиотека C# предоставляет профессиональное решение для онлайн-конвертирования файлов XLS в TSV. Этот Cloud SDK предоставляет разработчикам C# мощные функциональные возможности и обеспечивает высококачественный вывод TSV.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Пример кода для преобразования XLS в TSV с помощью Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xls";
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
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK for Net для преобразования файлов Excel в другие форматы XLS в TSV." >}}
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
