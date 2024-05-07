---
title:  Сохраните TSV как TXT, используя Java.
description:  Использование Aspose.Cells Cloud SDK for Java для сохранения файла формата TSV как файла формата TXT.
kwords: Excel, Save TSV as TXT, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save TSV as TXT using the Cells Cloud Java library.","description": "How to save TSV as TXT using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/tsv-to-txt/","step": [{ "@type": "HowToStep","name": "How to save TSV as TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/tsv-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save TSV as TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/tsv-to-txt/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save TSV as TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/tsv-to-txt/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save TSV as TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/tsv-to-txt/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить TSV как TXT" h2="Java библиотека для сохранения TSV в формате TXT" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Java. Это профессиональное решение для сохранения TSV в формате TXT и других форматов документов в Интернете с помощью Java." urlsection="saveas/tsv-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл TSV как TXT по номеру Java." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из TSV в формате TXT — сложная задача. Все переходы формата TSV в TXT выполняются нашим SDK Java с сохранением основного структурного и логического содержимого исходной таблицы TSV. Наша библиотека Java — это профессиональное решение для сохранения TSV в формате TXT в Интернете. Этот Cloud SDK предоставляет разработчикам Java мощные функциональные возможности и идеальный вывод TXT.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Пример кода для сохранения TSV как TXT с использованием REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.tsv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как сохранить TSV в формате TXT, используя библиотеку Cells Cloud Java." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Java и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Java.</li>
<li>Используйте метод `postWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Maven 2.2.0 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
