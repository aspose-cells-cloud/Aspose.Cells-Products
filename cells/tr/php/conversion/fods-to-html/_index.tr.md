﻿---
title:  FODS'yi Bulutta HTML'e dönüştürün via PHP
description: REST API ve Açık Kaynak PHP SDK ile Excel dosyaları oluşturun, düzenleyin veya dönüştürün
url: /tr/php/conversion/fods-to-html/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: HTML
platform: PHP
otherformats: ODS TXT XLT XLSX XML CSV TSV MHTML FODS DIF XLSB XLTM PDF XLSM MD TIFF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="PHP ile FODS\'yi HTML\'e dönüştür" h2="Excel ve OpenOffice dosya dönüştürmesini PHP için açık kaynaklı Cloud SDK ile otomatikleştirin" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS\'yi Hızlıca HTML via PHP\'e Dönüştürün" %}}
1.  adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlat
1. ```CellsApi.uploadFile``` yöntemiyle FODS dosyasını varsayılan Bulut Depolamaya yükleyin
1. Ortaya çıkan HTML dosyasını almak için ```CellsApi.cellsSaveAsPostDocumentSaveAs```'i arayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Excel API ve PHP SDK\'yı Kullanmaya Başlayın" %}}
 PHP kaynak kodu için Excel Cloud SDK'yı şuradan edinin:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) SDK'yı kendiniz derlemek veya[Salıverme](https://releases.aspose.cloud/) alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlı bir göz atın[API Referans](https://apireference.aspose.cloud/cells/) hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP FODS\'den HTML\'e Dönüştürme Kodu" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.html";
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