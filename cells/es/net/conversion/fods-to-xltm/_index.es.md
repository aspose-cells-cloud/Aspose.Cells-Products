﻿---
title:  Convertir FODS a XLTM via .NET
description: Cree, edite o convierta archivos Excel con Cloud API y Open Source .NET SDK
url: /es/net/conversion/fods-to-xltm/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: XLTM
platform: .NET
otherformats: XLTX XML XPS XLTM XLSM TXT MHTML TIFF ODS CSV SVG MD XLSB TSV PDF FODS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convierta FODS a XLTM en la nube" h2="Excel y conversión de hojas de cálculo de OpenOffice con Cloud SDK de código abierto for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversión de FODS a XLTM en aplicaciones .NET" %}}
1.  Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización
1. Inicialice ```CellsApi``` con ID de cliente, secreto de cliente, URL base y versión API
1. Cargue el archivo FODS al Cloud Storage predeterminado con el método ```CellsApi.Upload```
1. Llame al método ```CellsApi.CellsSaveAsPostDocumentSaveAs``` para obtener el archivo XLTM resultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Comience con Excel DESCANSO API" %}}
 Obtenga el código fuente Excel Cloud SDK for .NET de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) para compilar el SDK usted mismo o diríjase al[Lanzamientos](https://releases.aspose.cloud/) para opciones de descarga alternativas.

 También eche un vistazo a Basado en Swagger[API Referencia](https://apireference.aspose.cloud/cells/) para saber más sobre el[Excel DESCANSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Código para conversión de FODS a XLTM" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "xltm";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.xltm", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}