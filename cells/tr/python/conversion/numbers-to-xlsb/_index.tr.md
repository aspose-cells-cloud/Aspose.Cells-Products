﻿---
title:  NUMBERS - XLSB Dönüştür API için Python
description:  NUMBERS biçim dosyasını XLSB biçim dosyasına dönüştürmek için Python için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/python/conversion/numbers-to-xlsb/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NUMBERS\'i XLSB\'ye dönüştürmek için Python API" h2="NUMBERS\'i XLSB\'ye dönüştürmek için Python kitaplığı" p="Python\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, Python\'i kullanarak NUMBERS\'ı XLSB\'ye ve diğer belge biçimlerine çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/numbers-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir NUMBERS dosyasını Python\'de XLSB\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya biçimlerini NUMBERS'den XLSB'ye dönüştürmek karmaşık bir iştir. Tüm NUMBERS'tan XLSB'ye format geçişleri, kaynak NUMBERS e-tablonun ana yapısal ve mantıksal içeriği korunurken Python SDK'mız tarafından gerçekleştirilir. Python kitaplığımız, NUMBERS'i çevrimiçi olarak XLSB dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, Python geliştiricilerine güçlü işlevsellik ve mükemmel XLSB çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="SAYILARI XLSB formatına dönüştürmek için REST API kullanan Python\'deki kod örneği" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.numbers",format="xlsb")
    shutil.move(file1, "destFile.xlsb")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="NUMBERS\'i XLSB\'ye dönüştürmek için Python API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Çağrı hücreleri_çalışma kitabı_koymak_dönüştürmek_sonuç akışını almak için çalışma kitabı yöntemi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}