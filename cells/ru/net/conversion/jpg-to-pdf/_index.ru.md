﻿---
title:  JPG в PDF Конвертировать API в C#
description:  Облачные API и SDK для Microsoft Excel и OpenOffice Calc. Преобразование электронной таблицы в файл другого формата.
url: /ru/net/conversion/jpg-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API для преобразования JPG в PDF" h2="библиотека C# для преобразования JPG в PDF" p="Используйте Cells Conversion REST API для создания настраиваемых рабочих процессов электронных таблиц в Net. Это профессиональное решение для преобразования JPG в PDF и другие форматы документов онлайн с использованием C#." urlsection="conversion/jpg-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла JPG в PDF в C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из JPG в PDF — сложная задача. Все переходы между форматами JPG и PDF выполняются нашим SDK C# с сохранением основного структурного и логического содержимого исходной электронной таблицы JPG. Наша библиотека C# — это профессиональное решение для онлайн-конвертации JPG в файлы PDF. Этот облачный SDK предоставляет C# разработчикам мощную функциональность и идеальный результат PDF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в C# с использованием REST API для преобразования JPG в формат PDF" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.jpg";
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
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать C# API для преобразования JPG в PDF" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод CellsWorkbookPutConvertWorkbook, чтобы получить результирующий поток</li>
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