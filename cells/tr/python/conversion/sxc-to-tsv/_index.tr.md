---
title:  Python'i kullanarak SXC'yi TSV'ye dönüştürün
description:  SXC formatındaki bir dosyayı TSV formatındaki bir dosyaya dönüştürmek için Python için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert SXC to TSV, REST, Python
howto: How to convert SXC to TSV using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="SXC\'yi TSV\'ye dönüştür" h2="SXC\'yi TSV\'ye dönüştürmek için Python kitaplığı" p="Python projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Python\'i kullanarak SXC\'yi TSV\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/sxc-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="Python için Cells Cloud SDK\'yı kullanarak SXC\'yi TSV\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını SXC'den TSV'ye dönüştürmek karmaşık bir iş olabilir. Python SDK'mız, kaynak SXC elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm SXC'den TSV formatına dönüşümleri gerçekleştirir. Python kitaplığımız, SXC'yi çevrimiçi olarak TSV dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Python geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli TSV çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Cells Bulut SDK\'yı kullanarak SXC\'yi TSV\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.sxc",format="tsv")
    shutil.move(file1, "destFile.tsv")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Python kitaplığını kullanarak SXC\'yi TSV\'ye nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Python kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Python'de açın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
