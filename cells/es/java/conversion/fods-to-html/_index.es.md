﻿---
title:  Convierta FODS a HTML en la nube via Java
description: Cree, edite o convierta archivos Excel con REST API y Open Source Java SDK
url: /es/java/conversion/fods-to-html/
family: cells
platformtag: java
feature: conversion
informat: FODS
outformat: HTML
platform: Java
otherformats: XLSX XPS XLTX CSV MHTML PDF MD ODS XLTM DIF XLSM XLSB TIFF XML TSV TXT 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convierta FODS a HTML con Java" h2="Automatice Excel y la conversión de archivos de OpenOffice con el SDK de nube de código abierto for Java" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversión simple de FODS a HTML" %}}
1.  Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización
1. Inicialice ```CellsApi``` con ID de cliente, Secreto de cliente, URL base y versión API
1. Cargue el archivo FODS al almacenamiento en la nube predeterminado con el método ```CellsApi.Upload```
1. Llame al ```CellsApi.cellsWorkbookGetWorkbook``` para obtener el archivo HTML resultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Comience con Excel API y Java SDK" %}}
 Obtenga el código fuente Excel Cloud SDK for Java de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) para compilar el SDK usted mismo o diríjase a la[Lanzamientos](https://releases.aspose.cloud/) para opciones de descarga alternativas.

 También eche un vistazo a Swagger-based[API Referencia](https://apireference.aspose.cloud/cells/) para saber más sobre el[Excel DESCANSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Código para convertir FODS a HTML" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "HTML";
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