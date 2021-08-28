---
title: Convert XLSX to CSV on Android 
description: Automate Excel File Manipulation Operations with Cloud API & Open Source Android SDK
url: /android/conversion/xlsx-to-csv/
family: cells
platformtag: android
feature: conversion
informat: XLSX
outformat: CSV
platform: Android
otherformats: PDF TXT DIF XML CSV SVG ODS XLT XLTX TIFF MD XPS 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLSX to CSV in the Cloud" h2="Convert Excel & OpenOffice spreadsheets with open source Cloud SDK for Android">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSX to CSV Conversion in Android Apps" %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota as well as ClientId & ClientSecret
1. Initialize ~~~CellsApi~~~ with ClientId, ClientSecret, BaseURL & API version
1. Upload XLSX file to default Cloud Storage with ~~~CellsApiUtil.Upload~~~
1. Call ~~~CellsApi.cellsSaveAsPostDocumentSaveAs~~~ to convert workbook to CSV format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for Android source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) to compile the SDK yourself or head to the Repository if you are interested in JAR files. 

Also have a look at Swagger-based (API Reference)[https://apireference.aspose.cloud/cells/] to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: XLSX to CSV Conversion" gistPath="" %}}
```java
// for complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(),CellsApiUtil.GetClientSecret(),CellsApiUtil.GetAPIVersion(),CellsApiUtil.GetBaseUrl());
    String name = "template.xlsx";
    Boolean isAutoFitRows = true;
	Boolean isAutoFitColumns = true;
    String folder = TEMPFOLDER;
    CellsApiUtil.Upload(api, folder, name);
    File response = api.cellsSaveAsPostDocumentSaveAs(name, null, "output.csv", isAutoFitRows, isAutoFitColumns, folder, null);
}
catch (Exception e) {
    e.printStackTrace();
}
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}