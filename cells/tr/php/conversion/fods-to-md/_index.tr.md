---
title:  FODS'yi Bulutta MD'ye dönüştürün via PHP
description: REST API ve Açık Kaynak PHP SDK ile Excel dosyalarını oluşturun, düzenleyin veya dönüştürün
url: /tr/php/conversion/fods-to-md/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: MD
platform: PHP
otherformats: MD XLSX XPS TXT DIF MHTML XLTM CSV PDF XLSM TSV XLSB XML ODS XLTX SVG 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="PHP ile FODS\'yi MD\'ye dönüştürün" h2="Excel için açık kaynak Cloud SDK ile Excel ve OpenOffice dosya dönüştürmeyi otomatikleştirin" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS\'yi hızla MD\'ye dönüştürün via PHP" %}}
1.  Şu adreste bir hesap oluşturun:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın
1. FODS dosyasını ```CellsApi.uploadFile``` yöntemiyle varsayılan Cloud Storage'a yükleyin
1. Ortaya çıkan MD dosyasını almak için ```CellsApi.cellsSaveAsPostDocumentSaveAs```'i arayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Excel API ve PHP SDK\'yı Kullanmaya Başlayın" %}}
 PHP kaynak kodu için Excel Cloud SDK'yı şu adresten edinin:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) SDK'yı kendiniz derlemek veya[Salıverme](https://releases.aspose.cloud/) Alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlıya da bir göz atın[API Referans](https://apireference.aspose.cloud/cells/) hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP FODS\'den MD\'ye Dönüşüm Kodu" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.md";
$isAutoFitRows= 'true';
$isAutoFitColumns= 'true';
$folder = "Temp";
CellsApi::ready( $this->instance, $name, $folder );
$result = $this->instance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename, $isAutoFitRows, $isAutoFitColumns, $folder);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}