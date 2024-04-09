---
title:  Сохраните XLSX в формате JPG, используя Java.
description:  Использование Aspose.Cells Cloud SDK for Java для сохранения файла формата XLSX в формате JPG.
kwords: Excel, Save XLSX as JPG, REST, Java
howto: How to save XLSX as JPG using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить XLSX в формате JPG." h2="Java библиотека для сохранения XLSX в формате JPG" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Java. Это профессиональное решение для сохранения XLSX в формате JPG и других форматов документов в Интернете с помощью Java." urlsection="saveas/xlsx-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл XLSX в формате JPG по номеру Java." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение файлов формата XLSX в формате JPG — сложная задача. Все переходы формата XLSX в JPG выполняются нашим SDK Java с сохранением основного структурного и логического содержимого исходной электронной таблицы XLSX. Наша библиотека Java — это профессиональное решение для сохранения файлов XLSX в формате JPG онлайн. Этот Cloud SDK предоставляет разработчикам Java мощные функциональные возможности и идеальный вывод в формате JPG.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Пример кода для сохранения XLSX в формате JPG с использованием REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xlsx";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.jpg";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить XLSX в формате JPG, используя библиотеку Cells Cloud Java." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Java и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Java.</li>
<li>Используйте метод `postWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Maven 2.2.0 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
