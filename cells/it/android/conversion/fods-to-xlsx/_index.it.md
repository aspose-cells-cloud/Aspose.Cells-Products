﻿---
title:  Converti FODS in XLSX su Android
description: Automatizza Excel Operazioni di manipolazione dei file come creazione, modifica e conversione con Cloud API e SDK Android open source
url: /it/android/conversion/fods-to-xlsx/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: XLSX
platform: Android
otherformats: XML XLSB XLT XPS ODS XLTX TXT PDF TIFF DIF MD XLSM CSV XLSX XLTM SVG 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converti FODS in XLSX nel cloud" h2="Converti fogli di calcolo Excel e OpenOffice con Cloud SDK open source per Android" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversione da FODS a XLSX nelle app Android" %}}
1.  Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione
1. Inizializza ```CellsApi``` con ID client, segreto client, URL di base e versione API
1. Carica il file FODS nel Cloud Storage predefinito con il metodo ```CellsApiUtil.Upload```
1. Chiama lo ```CellsApi.cellsWorkbookGetWorkbook``` per ottenere il file XLSX risultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Inizia con Excel REST API" %}}
 Ottieni il codice sorgente di Excel Cloud SDK per ANDROID da[Git Hub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) per compilare tu stesso l'SDK o vai al file[Rilasci](https://releases.aspose.cloud/) per opzioni di download alternative.

 Dai anche un'occhiata a Swagger-based[API Riferimento](https://apireference.aspose.cloud/cells/) per saperne di più sul[Excel RIPOSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: conversione da FODS a XLSX" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "XLSX";
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