---
title:  Konvertieren Sie FODS auf Android in SVG
description: Automatisieren Sie Excel Dateibearbeitungsvorgänge wie Erstellung, Bearbeitung und Konvertierung mit Cloud API und Open Source Android SDK
url: /de/android/conversion/fods-to-svg/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: SVG
platform: Android
otherformats: XLSX SVG XLSM XLSB XML PDF MD DIF TSV TXT XLTM CSV XLTX ODS TIFF HTML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertieren Sie FODS in SVG in der Cloud" h2="Konvertieren Sie Excel- und OpenOffice-Tabellen mit Open Source Cloud SDK für Android" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierung von FODS in SVG in Android-Apps" %}}
1.  Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten
1. Initialisieren Sie ```CellsApi``` mit Client-ID, Client-Geheimnis, Basis-URL und API-Version
1. Laden Sie die FODS-Datei mit der Methode ```CellsApiUtil.Upload``` in den Standard-Cloud-Speicher hoch
1. Rufen Sie ```CellsApi.cellsWorkbookGetWorkbook``` an, um die resultierende SVG-Datei zu erhalten
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Beginnen Sie mit Excel REST API" %}}
 Holen Sie sich Excel Cloud SDK für ANDROID-Quellcode von[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) um das SDK selbst zu kompilieren oder gehen Sie zur[Freigaben](https://releases.aspose.cloud/) für alternative Download-Optionen.

 Schauen Sie sich auch Swagger-basiert an[API Referenz](https://apireference.aspose.cloud/cells/) um mehr über die zu erfahren[Excel RUHE API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: Umwandlung von FODS in SVG" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "SVG";
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