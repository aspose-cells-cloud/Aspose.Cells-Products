---
title:  Android'de FODS'yi SXC'ye dönüştürün
description: Bulut API ve Açık Kaynak Android SDK ile Oluşturma, Düzenleme ve Dönüştürme gibi Excel Dosya İşleme İşlemlerini otomatikleştirin
url: /tr/android/conversion/fods-to-sxc/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: SXC
platform: Android
otherformats: XLSB DIF XLSX CSV XLTM SVG FODS XML TXT MD XPS HTML TIFF TSV PDF XLSM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Bulutta FODS\'yi SXC\'ye dönüştürün" h2="Android için açık kaynaklı Cloud SDK ile Excel ve OpenOffice e-tablolarını dönüştürün" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Android Uygulamalarında FODS\'den SXC\'ye Dönüşüm" %}}
1.  Şu adreste bir hesap oluşturun:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın
1. FODS dosyasını ```CellsApiUtil.Upload``` yöntemiyle varsayılan Cloud Storage'a yükleyin
1. Ortaya çıkan SXC dosyasını almak için ```CellsApi.cellsWorkbookGetWorkbook```'i arayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Excel REST API ile Başlayın" %}}
 ANDROID kaynak kodu için Excel Cloud SDK'yı şu adresten edinin:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) SDK'yı kendiniz derlemek veya[Salıverme](https://releases.aspose.cloud/) Alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlıya da bir göz atın[API Referans](https://apireference.aspose.cloud/cells/) hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: FODS\'den SXC\'ye Dönüşüm" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "SXC";
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