---
title: Convert TXT to XLTX in the Cloud via Java 
description: Create, Edit or Convert Excel files with REST API & Open Source Java SDK
url: /java/conversion/txt-to-xltx/
family: cells
platformtag: java
feature: conversion
informat: TXT
outformat: XLTX
platform: Java
otherformats: XLT XLSB SVG XLTM TSV HTML XLTX CSV XLSM MD XLSX XML DIF SXC PDF ODS 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TXT to XLTX with Java" h2="Automate Excel & OpenOffice file conversion with open source Cloud SDK for Java">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Simple TXT to XLTX Conversion" %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Upload TXT file to default Cloud Storage with ```CellsApi.Upload``` method
1. Call ```CellsApi.cellsWorkbookGetWorkbook``` to get the resultant XLTX file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel API & Java SDK" %}}
Get Excel Cloud SDK for Java source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) to compile the SDK yourself or head to the [Releases](https://releases.aspose.cloud/) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Code to Convert TXT to XLTX" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "XLTX";
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