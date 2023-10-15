---
title:  Convertir FODS a XLTX en Android
description: Automatice las operaciones de manipulación de archivos Excel, como la creación, edición y conversión con Cloud API y el SDK de Android de código abierto
url: /es/android/conversion/fods-to-xltx/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: XLTX
platform: Android
otherformats: DIF MD MHTML TXT SVG XLSM XML XLSB PDF TIFF XLT XLTX FODS TSV XLSX XLTM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convierta FODS a XLTX en la nube" h2="Convierta hojas de cálculo Excel y OpenOffice con Cloud SDK de código abierto para Android" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversión de FODS a XLTX en aplicaciones de Android" %}}
1.  Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización
1. Inicialice ```CellsApi``` con ID de cliente, secreto de cliente, URL base y versión API
1. Cargue el archivo FODS al Cloud Storage predeterminado con el método ```CellsApiUtil.Upload```
1. Llame al ```CellsApi.cellsWorkbookGetWorkbook``` para obtener el archivo XLTX resultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Comience con Excel DESCANSO API" %}}
 Obtenga Excel Cloud SDK para el código fuente de ANDROID de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) para compilar el SDK usted mismo o diríjase al[Lanzamientos](https://releases.aspose.cloud/) para opciones de descarga alternativas.

 También eche un vistazo a Basado en Swagger[API Referencia](https://apireference.aspose.cloud/cells/) para saber más sobre el[Excel DESCANSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: conversión de FODS a XLTX" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "XLTX";
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