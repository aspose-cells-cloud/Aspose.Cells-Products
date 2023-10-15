---
title:  FODS'yi XLSM'ye dönüştürün via .NET
description: Cloud API ve Açık Kaynak .NET SDK ile Excel dosyalarını Oluşturun, Düzenleyin veya Dönüştürün
url: /tr/net/conversion/fods-to-xlsm/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: XLSM
platform: .NET
otherformats: XLS PDF FODS TSV XLSB MD XLT XML TXT XLSM SVG TIFF DIF XLSX MHTML XLTM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Bulutta FODS\'yi XLSM\'ye dönüştürün" h2="Excel ve açık kaynak Cloud SDK ile OpenOffice elektronik tablo dönüşümü for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET Uygulamalarında FODS\'den XLSM\'ye Dönüşüm" %}}
1.  Şu adreste bir hesap oluşturun:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın
1. FODS dosyasını ```CellsApi.Upload``` yöntemiyle varsayılan Cloud Storage'a yükleyin
1. Ortaya çıkan XLSM dosyasını almak için ```CellsApi.CellsSaveAsPostDocumentSaveAs``` yöntemini çağırın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Excel REST API ile Başlayın" %}}
 Excel Cloud SDK for .NET kaynak kodunu şu adresten alın:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) SDK'yı kendiniz derlemek veya[Salıverme](https://releases.aspose.cloud/) Alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlıya da bir göz atın[API Referans](https://apireference.aspose.cloud/cells/) hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET FODS\'den XLSM\'ye Dönüşüm Kodu" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "xlsm";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.xlsm", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}