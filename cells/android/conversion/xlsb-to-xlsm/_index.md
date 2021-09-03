---
title: Convert XLSB to XLSM on Android 
description: Automate Excel File Manipulation Operations such as Creation, Editing and Conversion with Cloud API & Open Source Android SDK
url: /android/conversion/xlsb-to-xlsm/
family: cells
platformtag: android
feature: conversion
informat: XLSB
outformat: XLSM
platform: Android
otherformats: DIF PDF MHTML SVG XLS CSV XPS SXC MD XLSM XLSX TIFF XML XLTM ODS TSV 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLSB to XLSM in the Cloud" h2="Convert Excel & OpenOffice spreadsheets with open source Cloud SDK for Android">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSB to XLSM Conversion in Android Apps" %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Upload XLSB file to default Cloud Storage with ```CellsApiUtil.Upload``` method
1. Call ```CellsApi.cellsWorkbookGetWorkbook``` to get the resultant XLSM file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for ANDROID source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) to compile the SDK yourself or head to the [Releases](https://releases.aspose.cloud/) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: XLSB to XLSM Conversion" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "XLSM";
    String folder = TEMPFOLDER;
    CellsApiUtil.Upload(api, folder, name);
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