﻿---
title:  Сохраните PNG как DOCX, используя Java.
description:  Использование Aspose.Cells Cloud SDK for Java для сохранения файла формата PNG как файла формата DOCX.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Сохранить PNG как DOCX" h2="Java библиотека для сохранения PNG как DOCX" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Java. Это профессиональное решение для сохранения PNG в формате DOCX и других форматов документов онлайн с использованием Java." urlsection="saveas/png-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл PNG как DOCX в Java." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение файлов формата PNG в формате DOCX — сложная задача. Все переходы формата PNG в формат DOCX выполняются нашим SDK Java с сохранением основного структурного и логического содержимого исходной таблицы PNG. Наша библиотека Java — это профессиональное решение для сохранения PNG в формате DOCX в Интернете. Этот Cloud SDK предоставляет разработчикам Java мощные функциональные возможности и идеальный вывод в формате DOCX.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Пример кода для сохранения PNG как DOCX с использованием REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.png";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.docx";
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
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK for Java для сохранения файлов Excel в других форматах PNG как DOCX" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Maven 2.2.0 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
