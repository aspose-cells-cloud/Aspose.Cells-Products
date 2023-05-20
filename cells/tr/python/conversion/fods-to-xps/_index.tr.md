---
title:  Excel FODS'i XPS via Python'e dönüştür
description: REST API ve Açık Kaynak Python SDK ile Excel dosyaları oluşturun, düzenleyin veya dönüştürün
url: /tr/python/conversion/fods-to-xps/
family: cells
platformtag: python
feature: conversion
informat: FODS
outformat: XPS
platform: Python
otherformats: XLTM DIF PDF MD SVG TIFF HTML XLTX TSV XLS CSV FODS XLSX XML XLSB XPS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Python ile FODS\'yi XPS\'e dönüştür" h2="Excel için açık kaynaklı Cloud SDK ile Excel verilerini okuyun, düzenleyin ve diğer biçimlere aktarın" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Python ile FODS\'den XPS\'e Dönüşüm" %}}
1.  adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlat
1. ```CellsApi.upload_file``` yöntemiyle FODS dosyasını varsayılan Bulut Depolamaya yükleyin
1. Ortaya çıkan XPS dosyasını almak için ```CellsApi.cells_save_as_post_document_save_as``` yöntemini çağırın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Excel API ve Python SDK\'yı Kullanmaya Başlayın" %}}
 Python kaynak kodu için Excel Cloud SDK'yı şuradan edinin:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python) SDK'yı kendiniz derlemek veya[Salıverme](https://releases.aspose.cloud/) alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlı bir göz atın[API Referans](https://apireference.aspose.cloud/cells/) hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Python FODS\'den XPS\'e Dönüştürme Kodu" gistPath="" %}}
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python
import os
import sys
import asposecellscloud
from asposecellscloud.apis.cells_api import CellsApi
api  = asposecellscloud.apis.cells_api.CellsApi(os.getenv('CellsCloudClientId'), os.getenv('CellsCloudClientSecret'), "v3.0" ,os.getenv('CellsCloudApiBaseUrl'))

name ='template.fods'    
saveOptions = None
newfilename = "output.xps"
isAutoFitRows= True
isAutoFitColumns= True
folder = "temp"
result = api.upload_file(folder + '/' + name,  "c:/TestData/" + name)
 
result = api.cells_save_as_post_document_save_as(name, save_options=saveOptions, newfilename=(folder +'/' + newfilename), is_auto_fit_rows=isAutoFitRows, is_auto_fit_columns=isAutoFitColumns, folder=folder)
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}