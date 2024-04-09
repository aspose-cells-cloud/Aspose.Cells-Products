---
title:  Сохраните TSV как PPTX, используя Java.
description:  Использование Aspose.Cells Cloud SDK for Java для сохранения файла формата TSV как файла формата PPTX.
kwords: Excel, Save TSV as PPTX, REST, Java
howto: How to save TSV as PPTX using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить TSV как PPTX" h2="Java библиотека для сохранения TSV как PPTX" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Java. Это профессиональное решение для сохранения TSV в формате PPTX и других форматов документов в Интернете с помощью Java." urlsection="saveas/tsv-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл TSV как PPTX по номеру Java." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из TSV в формате PPTX — сложная задача. Все переходы формата TSV в PPTX выполняются нашим SDK Java с сохранением основного структурного и логического содержимого исходной таблицы TSV. Наша библиотека Java — это профессиональное решение для сохранения TSV в виде файлов PPTX онлайн. Этот Cloud SDK предоставляет разработчикам Java мощные функциональные возможности и идеальный вывод PPTX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Пример кода для сохранения TSV как PPTX с использованием REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.tsv";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.pptx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить TSV в формате PPTX, используя библиотеку Cells Cloud Java." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Java и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Java.</li>
<li>Используйте метод `postWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Maven 2.2.0 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
