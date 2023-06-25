---
title: Сохранить EMF как TIFF API для Android
description:  Использование Aspose.Cells Cloud SDK для Android для сохранения файла формата EMF как файла формата TIFF.
url: /ru/android/saveas/emf-to-tiff/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API, чтобы сохранить EMF как TIFF" h2="Библиотека Android для сохранения EMF как TIFF" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Android. Это профессиональное решение для сохранения EMF как TIFF и других форматов документов в Интернете с помощью Android." urlsection="saveas/emf-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл EMF как TIFF в Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов с EMF как TIFF — сложная задача. Все переходы форматов с EMF на TIFF выполняются нашим Android SDK, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы EMF. Наша библиотека Android — это профессиональное решение для сохранения файлов EMF как TIFF онлайн. Этот облачный SDK предоставляет разработчикам Android мощные функциональные возможности и идеальный вывод TIFF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Android с использованием REST API для сохранения EMF в формате TIFF" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.emf";
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
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Java API, чтобы сохранить EMF как TIFF" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод cellSaveAsPostDocumentSaveAs, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Андроид 7 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
