---
title:  Android'de FODS'yi MHTML'ye dönüştürün
description: Bulut API ve Açık Kaynak Android SDK ile Oluşturma, Düzenleme ve Dönüştürme gibi Excel Dosya Manipülasyon İşlemlerini Otomatikleştirin
url: /tr/android/conversion/fods-to-mhtml/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: MHTML
platform: Android
otherformats: XML PDF TIFF XLTM XPS DIF XLSX ODS TXT FODS MD XLSM XLSB SVG CSV XLTX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="FODS\'yi Bulutta MHTML\'ye Dönüştürün" h2="Android için açık kaynaklı Cloud SDK ile Excel ve OpenOffice elektronik tablolarını dönüştürün" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Android Uygulamalarında FODS\'den MHTML\'ye Dönüşüm" %}}
1.  adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlat
1. ```CellsApiUtil.Upload``` yöntemiyle FODS dosyasını varsayılan Bulut Depolamaya yükleyin
1. Ortaya çıkan MHTML dosyasını almak için ```CellsApi.cellsWorkbookGetWorkbook```'i arayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Başlayın Excel REST API" %}}
 Excel Cloud SDK for ANDROID kaynak kodunu şu adresten edinin:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) SDK'yı kendiniz derlemek veya[Salıverme](https://releases.aspose.cloud/) alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlı bir göz atın[API Referans](https://apireference.aspose.cloud/cells/) hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: FODS\'den MHTML\'ye Dönüşüm" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "MHTML";
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