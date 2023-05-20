---
title:  FODS'yi XLTX'e dönüştür via .NET
description: Cloud API ve Açık Kaynak .NET SDK ile Excel dosyaları oluşturun, düzenleyin veya dönüştürün
url: /tr/net/conversion/fods-to-xltx/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: XLTX
platform: .NET
otherformats: XLS MHTML XML XLTX XLSM ODS MD SVG XLTM DIF TIFF XLSB XPS PDF TXT XLSX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="FODS\'yi Bulutta XLTX\'e Dönüştürün" h2="Excel ve açık kaynaklı Cloud SDK for .NET ile OpenOffice elektronik tablo dönüştürme" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET Uygulamalarında FODS\'den XLTX\'e Dönüştürme" %}}
1.  adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlat
1. ```CellsApi.Upload``` yöntemiyle FODS dosyasını varsayılan Bulut Depolamaya yükleyin
1. Ortaya çıkan XLTX dosyasını almak için ```CellsApi.CellsSaveAsPostDocumentSaveAs``` yöntemini çağırın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Başlayın Excel REST API" %}}
 Excel Cloud SDK for .NET kaynak kodunu şu adresten alın:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) SDK'yı kendiniz derlemek veya[Salıverme](https://releases.aspose.cloud/) alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlı bir göz atın[API Referans](https://apireference.aspose.cloud/cells/) hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET FODS\'den XLTX\'e Dönüşüm Kodu" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "xltx";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.xltx", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}