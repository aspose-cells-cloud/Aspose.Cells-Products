﻿---
title:  Konvertieren Sie FODS in CSV in der Cloud via Java
description: Erstellen, bearbeiten oder konvertieren Sie Excel-Dateien mit REST API und Open Source Java SDK
url: /de/java/conversion/fods-to-csv/
family: cells
platformtag: java
feature: conversion
informat: FODS
outformat: CSV
platform: Java
otherformats: XLSB DIF XLSX XPS XLTX PDF XML XLSM CSV MD HTML FODS XLTM TSV SVG MHTML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertieren Sie FODS mit Java in CSV" h2="Automatisieren Sie die Excel- und OpenOffice-Dateikonvertierung mit dem Open-Source-Cloud-SDK for Java" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Einfache Konvertierung von FODS in CSV" %}}
1.  Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten
1. Initialisieren Sie ```CellsApi``` mit Client-ID, Client-Geheimnis, Basis-URL und Version API
1. Laden Sie die FODS-Datei mit der Methode ```CellsApi.Upload``` in den Standard-Cloud-Speicher hoch
1. Rufen Sie ```CellsApi.cellsWorkbookGetWorkbook``` an, um die resultierende CSV-Datei zu erhalten
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Beginnen Sie mit dem SDK Excel, API und Java" %}}
 Holen Sie sich den Quellcode Excel Cloud SDK for Java von[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) um das SDK selbst zu kompilieren oder gehen Sie zu[Veröffentlichungen](https://releases.aspose.cloud/) für alternative Download-Optionen.

 Schauen Sie sich auch Swagger-basierte[API Referenz](https://apireference.aspose.cloud/cells/) Erfahren Sie mehr über die[Excel RUHET API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Code zum Konvertieren von FODS in CSV" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "CSV";
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