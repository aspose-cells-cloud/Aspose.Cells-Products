﻿---
title:  Сохранить НОМЕРА как EMF API для Android
description:  Облачные API и SDK для Microsoft Excel и OpenOffice Calc. Преобразование электронной таблицы в файл другого формата.
url: /ru/android/saveas/numbers-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API для сохранения NUMBERS как EMF" h2="Библиотека Android для сохранения NUMBERS как EMF" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Android. Это профессиональное решение для сохранения NUMBERS как EMF и других форматов документов онлайн с помощью Android." urlsection="saveas/numbers-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл NUMBERS как EMF в Android." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из NUMBERS как EMF — сложная задача. Все преобразования форматов NUMBERS в EMF выполняются нашим Android SDK, при этом сохраняется основное структурное и логическое содержание исходной электронной таблицы NUMBERS. Наша библиотека для Android — это профессиональное решение для сохранения файлов NUMBERS в формате EMF онлайн. Этот облачный SDK предоставляет разработчикам Android мощные функциональные возможности и идеальный вывод EMF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Android с использованием REST API для сохранения NUMBERS в формате EMF" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.numbers";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.emf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Java API, чтобы сохранить НОМЕРА как EMF" >}}
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