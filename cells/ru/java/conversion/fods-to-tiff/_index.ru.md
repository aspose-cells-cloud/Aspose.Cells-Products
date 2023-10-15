---
title:  Преобразование FODS в TIFF в облаке via Java
description: Создавайте, редактируйте или конвертируйте файлы Excel с помощью REST API и SDK с открытым исходным кодом Java.
url: /ru/java/conversion/fods-to-tiff/
family: cells
platformtag: java
feature: conversion
informat: FODS
outformat: TIFF
platform: Java
otherformats: XLT HTML CSV FODS XLS XLTM XLSB XLSX MHTML XLSM TSV MD XML PDF DIF XPS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразуйте FODS в TIFF с помощью Java" h2="Автоматизируйте преобразование файлов Excel и OpenOffice с помощью Cloud SDK с открытым исходным кодом for Java" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Простое преобразование FODS в TIFF" %}}
1.  Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API
1. Инициализируйте ```CellsApi```, используя идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.
1. Загрузите файл FODS в облачное хранилище по умолчанию с помощью метода ```CellsApi.Upload```.
1. Позвоните по номеру ```CellsApi.cellsWorkbookGetWorkbook```, чтобы получить результирующий файл TIFF.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начало работы с Excel, API и Java SDK" %}}
 Получите исходный код Excel Cloud SDK for Java с сайта[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) скомпилировать SDK самостоятельно или перейти к[Релизы](https://releases.aspose.cloud/) альтернативные варианты загрузки.

 Также взгляните на Swagger на основе[API Ссылка](https://apireference.aspose.cloud/cells/) чтобы узнать больше о[Excel ОТДЫХ API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Код для преобразования FODS в TIFF" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "TIFF";
    String folder = TEMPFOLDER;
    api.uploadFile( folder +"/"+ name, new File("c:\\TestData\\" + name) , null);
    File response = api.cellsWorkbookGetWorkbook(name, password, format, isAutoFit, onlySaveTable, folder, null, null);
}
catch (Exception e) {
    e.printStackTrace();
}
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}