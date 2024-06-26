﻿---
title:  Сохраните ЧИСЛА как DIF с помощью Android
description:  Использование Aspose.Cells Cloud SDK для Android для сохранения файла формата NUMBERS в формате DIF.
kwords: Excel, Save NUMBERS as DIF, REST, Android
howto: How to save NUMBERS as DIF using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить ЧИСЛА как DIF" h2="Библиотека Android для сохранения ЧИСЕЛ в формате DIF" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Android. Это профессиональное решение для сохранения ЧИСЕЛ в формате DIF и других форматов документов онлайн с помощью Android." urlsection="saveas/numbers-to-dif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл NUMBERS как DIF в Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из NUMBERS в формате DIF — сложная задача. Все переходы формата NUMBERS в DIF выполняются нашим Android SDK с сохранением основного структурного и логического содержимого исходной таблицы NUMBERS. Наша библиотека Android — это профессиональное решение для сохранения ЧИСЕЛ в виде файлов DIF онлайн. Этот Cloud SDK предоставляет разработчикам Android мощные функциональные возможности и идеальный вывод в формате DIF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Android для сохранения ЧИСЕЛ в формате DIF с использованием REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.numbers";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.dif";
    String folder ="CellsTests";
    try
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Android для сохранения файлов Excel в других форматах" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Android 7 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
