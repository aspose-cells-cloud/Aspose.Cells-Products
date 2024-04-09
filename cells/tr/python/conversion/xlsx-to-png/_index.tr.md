---
title:  Python'i kullanarak XLSX'i PNG'e dönüştürün
description:  XLSX biçimindeki bir dosyayı PNG biçimindeki bir dosyaya dönüştürmek için Python için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Convert XLSX to PNG, REST, Python
howto: How to convert XLSX to PNG using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="XLSX\'i PNG\'e dönüştür" h2="XLSX\'i PNG\'e dönüştürmek için Python kütüphanesi" p="Python projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Python\'i kullanarak XLSX\'i PNG\'e ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xlsx-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Python için Cells Cloud SDK\'yı kullanarak XLSX\'i PNG\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLSX'ten PNG'e dönüştürmek karmaşık bir iş olabilir. Python SDK'mız, kaynak XLSX elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm XLSX'ten PNG formatına dönüşümleri gerçekleştirir. Python kitaplığımız, XLSX'i çevrimiçi olarak PNG dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Python geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli PNG çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Cells Cloud SDK\'yı kullanarak XLSX\'i PNG\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlsx",format="png")
    shutil.move(file1, "destFile.png")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Python kitaplığını kullanarak XLSX\'i PNG\'e nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Python kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Python'de açın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
