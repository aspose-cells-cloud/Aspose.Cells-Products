---
title:  Bulutta FODS'yi MHTML'ye dönüştürün via Java
description: REST API ve Açık Kaynak Java SDK ile Excel dosyalarını oluşturun, düzenleyin veya dönüştürün
url: /tr/java/conversion/fods-to-mhtml/
family: cells
platformtag: java
feature: conversion
informat: FODS
outformat: MHTML
platform: Java
otherformats: TXT MHTML CSV XPS TIFF XLTX DIF FODS XML XLSB MD XLTM PDF XLSM XLSX SVG 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Java ile FODS\'yi MHTML\'ye dönüştürün" h2="Açık kaynak Cloud SDK for Java ile Excel ve OpenOffice dosya dönüştürmeyi otomatikleştirin" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Basit FODS\'den MHTML\'ye Dönüşüm" %}}
1.  Şu adreste bir hesap oluşturun:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın
1. FODS dosyasını ```CellsApi.Upload``` yöntemiyle varsayılan Cloud Storage'a yükleyin
1. Ortaya çıkan MHTML dosyasını almak için ```CellsApi.cellsWorkbookGetWorkbook```'i arayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Excel API ve Java SDK\'yı Kullanmaya Başlayın" %}}
 Excel Cloud SDK for Java kaynak kodunu şu adresten alın:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) SDK'yı kendiniz derlemek veya[Salıverme](https://releases.aspose.cloud/) Alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlıya da bir göz atın[API Referans](https://apireference.aspose.cloud/cells/) hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java FODS\'yi MHTML\'ye Dönüştürme Kodu" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "MHTML";
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