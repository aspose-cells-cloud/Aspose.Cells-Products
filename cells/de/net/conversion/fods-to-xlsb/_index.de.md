---
title:  Konvertieren Sie FODS in XLSB via .NET
description: Erstellen, bearbeiten oder konvertieren Sie Excel-Dateien mit Cloud API und Open Source .NET SDK
url: /de/net/conversion/fods-to-xlsb/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: XLSB
platform: .NET
otherformats: DIF XLSX TSV XLT XLSB MD TXT XML PDF SVG ODS TIFF XPS XLTX MHTML CSV 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertieren Sie FODS in XLSB in der Cloud" h2="Excel & OpenOffice-Tabellenkonvertierung mit Open-Source-Cloud-SDK for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierung von FODS in XLSB in .NET-Apps" %}}
1.  Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten
1. Initialisieren Sie ```CellsApi``` mit Client-ID, Client-Geheimnis, Basis-URL und Version API
1. Laden Sie die FODS-Datei mit der Methode ```CellsApi.Upload``` in den Standard-Cloud-Speicher hoch
1. Rufen Sie die Methode ```CellsApi.CellsSaveAsPostDocumentSaveAs``` auf, um die resultierende XLSB-Datei abzurufen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Beginnen Sie mit Excel REST API" %}}
 Holen Sie sich den Quellcode Excel Cloud SDK for .NET von[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) um das SDK selbst zu kompilieren oder gehen Sie zu[Veröffentlichungen](https://releases.aspose.cloud/) für alternative Download-Optionen.

 Schauen Sie sich auch Swagger-based an[API Referenz](https://apireference.aspose.cloud/cells/) um mehr darüber zu erfahren[Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Code für die Konvertierung von FODS in XLSB" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "xlsb";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.xlsb", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}