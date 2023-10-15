---
title:  Преобразовать FODS в HTML via .NET
description: Создавайте, редактируйте или конвертируйте файлы Excel с помощью Cloud API и SDK с открытым исходным кодом .NET.
url: /ru/net/conversion/fods-to-html/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: HTML
platform: .NET
otherformats: XML XLT XLTM XLTX SVG XLSB TXT ODS TSV DIF PDF TIFF MD XLSM MHTML CSV 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразование FODS в HTML в облаке" h2="Excel и преобразование электронных таблиц OpenOffice с помощью Cloud SDK с открытым исходным кодом for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Преобразование FODS в HTML в приложениях .NET" %}}
1.  Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API
1. Инициализируйте ```CellsApi```, используя идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.
1. Загрузите файл FODS в облачное хранилище по умолчанию с помощью метода ```CellsApi.Upload```.
1. Вызовите метод ```CellsApi.CellsSaveAsPostDocumentSaveAs```, чтобы получить результирующий файл HTML.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начните с Excel REST API" %}}
 Получите исходный код Excel Cloud SDK for .NET с сайта[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) скомпилировать SDK самостоятельно или перейти к[Релизы](https://releases.aspose.cloud/) альтернативные варианты загрузки.

 Также взгляните на Swagger на основе[API Ссылка](https://apireference.aspose.cloud/cells/) чтобы узнать больше о[Excel ОТДЫХ API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Код для преобразования FODS в HTML" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "html";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.html", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}