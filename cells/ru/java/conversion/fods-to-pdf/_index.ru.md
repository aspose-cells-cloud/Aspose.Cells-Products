---
title:  Преобразование FODS в PDF в облаке via Java
description: Создавайте, редактируйте или конвертируйте Excel файлы с помощью REST API и Open Source Java SDK
url: /ru/java/conversion/fods-to-pdf/
family: cells
platformtag: java
feature: conversion
informat: FODS
outformat: PDF
platform: Java
otherformats: DIF XLT MD MHTML TIFF XPS XLTM XLTX TSV PDF XLSB SVG ODS FODS XLSX CSV 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразование FODS в PDF с помощью Java" h2="Автоматизируйте преобразование файлов Excel и OpenOffice с помощью Cloud SDK с открытым исходным кодом for Java" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Простое преобразование FODS в PDF" %}}
1.  Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API
1. Инициализируйте ```CellsApi``` с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.
1. Загрузите файл FODS в облачное хранилище по умолчанию с помощью метода ```CellsApi.Upload```.
1. Позвоните по номеру ```CellsApi.cellsWorkbookGetWorkbook```, чтобы получить результирующий файл PDF.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начните работу с Excel, API и Java SDK" %}}
 Получите исходный код Excel Cloud SDK for Java из[Гитхаб](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) скомпилировать SDK самостоятельно или обратиться к[Релизы](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

 Также взгляните на Swagger-based[API Ссылка](https://apireference.aspose.cloud/cells/) узнать больше о[Excel ОТДЫХ API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Код для преобразования FODS в PDF" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "PDF";
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