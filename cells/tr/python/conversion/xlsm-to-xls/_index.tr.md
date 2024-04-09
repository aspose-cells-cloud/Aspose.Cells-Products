---
title:  Python'i kullanarak XLSM'yi XLS'ye dönüştürün
description:  XLSM biçimindeki bir dosyayı XLS biçimindeki dosyaya dönüştürmek için Python için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Convert XLSM to XLS, REST, Python
howto: How to convert XLSM to XLS using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="XLSM\'yi XLS\'ye dönüştür" h2="XLSM\'yi XLS\'ye dönüştürmek için Python kütüphane" p="Python projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Python numaralı telefonu kullanarak XLSM\'yi XLS\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xlsm-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="Python için Cells Cloud SDK\'yı kullanarak XLSM\'yi XLS\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLSM'den XLS'ye dönüştürmek karmaşık bir iş olabilir. Python SDK'mız, kaynak XLSM elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm XLSM'den XLS formatına dönüşümleri gerçekleştirir. Python kitaplığımız, XLSM'yi çevrimiçi olarak XLS dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Python geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli XLS çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Cells Bulut SDK\'yı kullanarak XLSM\'yi XLS\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlsm",format="xls")
    shutil.move(file1, "destFile.xls")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Python kitaplığını kullanarak XLSM\'yi XLS\'ye nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Python kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Python'de açın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
