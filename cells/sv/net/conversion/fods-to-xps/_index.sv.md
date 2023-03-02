---
title:  Convertir FODS a XPS via .NET
description: Cree, edite o convierta archivos Excel con Cloud API y Open Source .NET SDK
url: /sv/net/conversion/fods-to-xps/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: XPS
platform: .NET
otherformats: MD XML SVG TSV XPS XLSM PDF TXT FODS TIFF XLSB XLTM XLSX HTML DIF MHTML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convierta FODS a XPS en la nube" h2="Excel y conversión de hoja de cálculo de OpenOffice con SDK de nube de código abierto for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS a XPS Conversión en .NET Aplicaciones" %}}
1.  Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización
1. Inicialice ```CellsApi``` con ID de cliente, Secreto de cliente, URL base y versión API
1. Cargue el archivo FODS al almacenamiento en la nube predeterminado con el método ```CellsApi.Upload```
1. Llame al método ```CellsApi.CellsSaveAsPostDocumentSaveAs``` para obtener el archivo XPS resultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Comience con Excel DESCANSO API" %}}
 Obtenga el código fuente Excel Cloud SDK for .NET de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) para compilar el SDK usted mismo o diríjase a la[Lanzamientos](https://releases.aspose.cloud/) para opciones de descarga alternativas.

 También eche un vistazo a Swagger-based[API Referencia](https://apireference.aspose.cloud/cells/) para saber más sobre el[Excel DESCANSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Código para FODS a XPS Conversión" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "xps";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.xps", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}