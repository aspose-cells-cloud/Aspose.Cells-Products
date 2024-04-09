---
title:  Сохраните XLSX как TIFF, используя Java.
description:  Использование Aspose.Cells Cloud SDK for Java для сохранения файла формата XLSX как файла формата TIFF.
kwords: Excel, Save XLSX as TIFF, REST, Java
howto: How to save XLSX as TIFF using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить XLSX как TIFF." h2="Java библиотека для сохранения XLSX как TIFF" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Java. Это профессиональное решение для сохранения XLSX как TIFF и других форматов документов онлайн с использованием Java." urlsection="saveas/xlsx-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл XLSX как TIFF в Java." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение файлов формата XLSX как TIFF — сложная задача. Все переходы формата XLSX в TIFF выполняются нашим SDK Java с сохранением основного структурного и логического содержимого исходной таблицы XLSX. Наша библиотека Java — это профессиональное решение для сохранения файлов XLSX в формате TIFF онлайн. Этот Cloud SDK предоставляет разработчикам Java мощные функциональные возможности и идеальный результат TIFF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Пример кода для сохранения XLSX как TIFF с использованием REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xlsx";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.tiff";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить XLSX как TIFF, используя библиотеку Cells Cloud Java." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Java и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Java.</li>
<li>Используйте метод `postWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Maven 2.2.0 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
