---
title: Konvertera FODS till XLS i molnet via Java
description: Skapa, redigera eller konvertera Excel-filer med REST API & Open Source Java SDK
url: /sv/java/conversion/fods-to-xls/
family: cells
platformtag: java
feature: conversion
informat: FODS
outformat: XLS
platform: Java
otherformats: XLTM SVG HTML CSV XML DIF XLTX TIFF PDF MD MHTML XLSX ODS FODS XLSM TXT 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertera FODS till XLS med Java" h2="Automatisera Excel & OpenOffice-filkonvertering med open source Cloud SDK for Java" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Enkel FODS till XLS-konvertering" %}}
1.  Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation
1. Initiera ```CellsApi``` med klient-id, klienthemlighet, basadress och API-version
1. Ladda upp FODS-fil till standardmolnlagring med metoden ```CellsApi.Upload```
1. Ring ```CellsApi.cellsWorkbookGetWorkbook``` för att få den resulterande XLS-filen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kom igång med Excel API & Java SDK" %}}
 Få Excel Cloud SDK for Java källkod från[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) för att kompilera SDK själv eller gå till[Släpps](https://releases.aspose.cloud/) för alternativa nedladdningsalternativ.

 Ta också en titt på Swagger-baserad[API Referens](https://apireference.aspose.cloud/cells/) att veta mer om[Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Kod för att konvertera FODS till XLS" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "XLS";
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