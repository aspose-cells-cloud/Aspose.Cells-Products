---
title:  Bulutta FODS'yi TXT'ye dönüştürün via Java
description: REST API ve Açık Kaynak Java SDK ile Excel dosyaları oluşturun, düzenleyin veya dönüştürün
url: /tr/java/conversion/fods-to-txt/
family: cells
platformtag: java
feature: conversion
informat: FODS
outformat: TXT
platform: Java
otherformats: XLSB ODS XLSX CSV HTML XLTX DIF XLTM TSV XML MHTML XLSM TIFF XPS SVG FODS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Java ile FODS\'yi TXT\'ye dönüştürün" h2="Açık kaynaklı Cloud SDK for Java ile Excel ve OpenOffice dosya dönüştürmeyi otomatikleştirin" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Basit FODS\'den TXT\'ye Dönüşüm" %}}
1.  adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlat
1. ```CellsApi.Upload``` yöntemiyle FODS dosyasını varsayılan Bulut Depolamaya yükleyin
1. Ortaya çıkan TXT dosyasını almak için ```CellsApi.cellsWorkbookGetWorkbook```'i arayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Excel API ve Java SDK\'yı Kullanmaya Başlayın" %}}
 Excel Cloud SDK for Java kaynak kodunu şu adresten alın:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) SDK'yı kendiniz derlemek veya[Salıverme](https://releases.aspose.cloud/) alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlı bir göz atın[API Referans](https://apireference.aspose.cloud/cells/) hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java FODS\'yi TXT\'ye Dönüştürmek İçin Kod" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "TXT";
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