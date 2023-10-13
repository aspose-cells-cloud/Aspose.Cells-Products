﻿---
title:  Convertir FODS a TSV en Android
description: Automatice las operaciones de manipulación de archivos Excel, como la creación, edición y conversión con la nube API y el SDK de Android de código abierto
url: /es/android/conversion/fods-to-tsv/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: TSV
platform: Android
otherformats: XLS XLTM XML CSV PDF ODS HTML XPS TIFF MD TSV DIF TXT FODS XLSX MHTML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convierta FODS a TSV en la nube" h2="Convierta Excel y hojas de cálculo de OpenOffice con Cloud SDK de código abierto para Android" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversión de FODS a TSV en aplicaciones de Android" %}}
1.  Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización
1. Inicialice ```CellsApi``` con ID de cliente, Secreto de cliente, URL base y versión API
1. Cargue el archivo FODS al almacenamiento en la nube predeterminado con el método ```CellsApiUtil.Upload```
1. Llame al ```CellsApi.cellsWorkbookGetWorkbook``` para obtener el archivo TSV resultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Comience con Excel DESCANSO API" %}}
 Obtenga el código fuente Excel Cloud SDK para ANDROID de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) para compilar el SDK usted mismo o diríjase a la[Lanzamientos](https://releases.aspose.cloud/) para opciones de descarga alternativas.

 También eche un vistazo a Swagger-based[API Referencia](https://apireference.aspose.cloud/cells/) para saber más sobre el[Excel DESCANSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: conversión de FODS a TSV" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "TSV";
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