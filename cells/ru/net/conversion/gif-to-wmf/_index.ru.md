﻿---
title:  Преобразование GIF в WMF API для C#
description:  Облачные API и SDK для Microsoft Excel и OpenOffice Calc. Преобразование электронной таблицы в файл другого формата.
url: /ru/net/conversion/gif-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API для преобразования GIF в WMF" h2="C# библиотека для преобразования GIF в WMF" p="Используйте Cells Conversion REST API для создания настраиваемых рабочих процессов электронных таблиц в Net. Это профессиональное решение для преобразования GIF в WMF и другие форматы документов онлайн с помощью C#." urlsection="conversion/gif-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла GIF в WMF в C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из GIF в WMF — сложная задача. Все переходы формата GIF в WMF выполняются нашим SDK C#, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы GIF. Наша библиотека C# — это профессиональное решение для онлайн-конвертации файлов GIF в WMF. Этот облачный SDK предоставляет C# разработчикам мощную функциональность и идеальный вывод WMF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в C# с использованием REST API для преобразования GIF в формат WMF" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.gif";
    string format = "wmf";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.wmf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать C# API для преобразования GIF в WMF" >}}
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