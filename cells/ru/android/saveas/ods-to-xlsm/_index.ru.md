﻿---
title:  Сохраните ODS как XLSM с помощью Android
description:  Использование Aspose.Cells Cloud SDK для Android для сохранения файла формата ODS в формате XLSM.
kwords: Excel, Save ODS as XLSM, REST, Android
howto: How to save ODS as XLSM using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить ODS как XLSM" h2="Библиотека Android для сохранения ODS в формате XLSM" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Android. Это профессиональное решение для сохранения ODS в формате XLSM и других форматов документов онлайн с помощью Android." urlsection="saveas/ods-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл ODS как XLSM на Android." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из ODS в формате XLSM — сложная задача. Все переходы формата ODS в XLSM выполняются нашим Android SDK с сохранением основного структурного и логического содержимого исходной электронной таблицы ODS. Наша библиотека Android — это профессиональное решение для сохранения файлов ODS в формате XLSM онлайн. Этот Cloud SDK предоставляет разработчикам Android мощные функциональные возможности и идеальный вывод XLSM.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Android для сохранения ODS как XLSM с использованием REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.ods";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xlsm";
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
