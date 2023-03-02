---
title:  Konvertieren Sie FODS in TSV via .NET
description: Erstellen, bearbeiten oder konvertieren Sie Excel-Dateien mit Cloud API & Open Source .NET SDK
url: /de/net/conversion/fods-to-tsv/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: TSV
platform: .NET
otherformats: MHTML DIF ODS XPS XLS XLSX XLSM TXT TIFF TSV XLTM MD PDF CSV FODS XLSB 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertieren Sie FODS in TSV in der Cloud" h2="Excel & OpenOffice-Tabellenkonvertierung mit Open Source Cloud SDK for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierung von FODS in TSV in .NET-Apps" %}}
1.  Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten
1. Initialisieren Sie ```CellsApi``` mit Client-ID, Client-Geheimnis, Basis-URL und API-Version
1. Laden Sie die FODS-Datei mit der Methode ```CellsApi.Upload``` in den Standard-Cloud-Speicher hoch
1. Rufen Sie die Methode ```CellsApi.CellsSaveAsPostDocumentSaveAs``` auf, um die resultierende TSV-Datei abzurufen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Beginnen Sie mit Excel REST API" %}}
 Holen Sie sich den Excel Cloud SDK for .NET-Quellcode von[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) um das SDK selbst zu kompilieren oder gehen Sie zur[Freigaben](https://releases.aspose.cloud/) für alternative Download-Optionen.

 Schauen Sie sich auch Swagger-basiert an[API Referenz](https://apireference.aspose.cloud/cells/) um mehr über die zu erfahren[Excel RUHE API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Code für die Umwandlung von FODS in TSV" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "tsv";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.tsv", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}