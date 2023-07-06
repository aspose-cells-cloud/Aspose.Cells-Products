---
title:  Konvertieren Sie FODS in PDF auf Android
description: Automatisieren Sie Excel Dateimanipulationsvorgänge wie Erstellung, Bearbeitung und Konvertierung mit Cloud API und Open Source Android SDK
url: /de/android/conversion/fods-to-pdf/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: PDF
platform: Android
otherformats: XLSX DIF CSV XML TSV PDF MD HTML XLTX TIFF TXT FODS XLSM SVG MHTML XPS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertieren Sie FODS in der Cloud in PDF" h2="Konvertieren Sie Excel- und OpenOffice-Tabellen mit dem Open-Source-Cloud-SDK für Android" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierung von FODS in PDF in Android-Apps" %}}
1.  Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten
1. Initialisieren Sie ```CellsApi``` mit Client-ID, Client-Geheimnis, Basis-URL und Version API
1. Laden Sie die FODS-Datei mit der Methode ```CellsApiUtil.Upload``` in den Standard-Cloud-Speicher hoch
1. Rufen Sie ```CellsApi.cellsWorkbookGetWorkbook``` an, um die resultierende Datei PDF zu erhalten
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Beginnen Sie mit Excel REST API" %}}
 Holen Sie sich den Quellcode Excel Cloud SDK für ANDROID von[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) um das SDK selbst zu kompilieren oder gehen Sie zu[Veröffentlichungen](https://releases.aspose.cloud/) für alternative Download-Optionen.

 Schauen Sie sich auch Swagger-based an[API Referenz](https://apireference.aspose.cloud/cells/) um mehr darüber zu erfahren[Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: Konvertierung von FODS zu PDF" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "PDF";
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