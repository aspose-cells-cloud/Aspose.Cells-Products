﻿---
title:  Сохраните XML как TXT с помощью Android
description:  Использование Aspose.Cells Cloud SDK для Android для сохранения файла формата XML в формате TXT.
kwords: Excel, Save XML as TXT, REST, Android
howto: How to save XML as TXT using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить XML как TXT" h2="Библиотека Android для сохранения XML в формате TXT" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Android. Это профессиональное решение для сохранения XML в формате TXT и других форматов документов онлайн с помощью Android." urlsection="saveas/xml-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните XML-файл как TXT в Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из XML в формате TXT — сложная задача. Все переходы формата XML в TXT выполняются нашим Android SDK, сохраняя при этом основное структурное и логическое содержимое исходной XML-таблицы. Наша библиотека Android — это профессиональное решение для сохранения XML в формате TXT в Интернете. Этот Cloud SDK предоставляет разработчикам Android мощные функциональные возможности и идеальный вывод TXT.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Android для сохранения XML в формате TXT с использованием REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xml";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.txt";
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
