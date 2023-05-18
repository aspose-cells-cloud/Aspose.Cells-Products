---
title:  Converti FODS in SVG nel Cloud via Java
description: Crea, modifica o converti file Excel con REST API e Open Source Java SDK
url: /it/java/conversion/fods-to-svg/
family: cells
platformtag: java
feature: conversion
informat: FODS
outformat: SVG
platform: Java
otherformats: XLTX TSV XLSX MD FODS PDF TXT DIF XLTM HTML TIFF SVG XPS XML MHTML CSV 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converti FODS in SVG con Java" h2="Automatizza la conversione dei file Excel e OpenOffice con Cloud SDK open source for Java" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversione da FODS semplice a SVG" %}}
1.  Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione
1. Inizializza ```CellsApi``` con ID client, segreto client, URL di base e versione API
1. Carica il file FODS nel Cloud Storage predefinito con il metodo ```CellsApi.Upload```
1. Chiama lo ```CellsApi.cellsWorkbookGetWorkbook``` per ottenere il file SVG risultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Inizia con Excel API e Java SDK" %}}
 Ottieni il codice sorgente Excel Cloud SDK for Java da[Git Hub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) per compilare tu stesso l'SDK o vai al file[Rilasci](https://releases.aspose.cloud/) per opzioni di download alternative.

 Dai anche un'occhiata a Swagger-based[API Riferimento](https://apireference.aspose.cloud/cells/) per saperne di più sul[Excel RIPOSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Codice per convertire FODS in SVG" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "SVG";
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