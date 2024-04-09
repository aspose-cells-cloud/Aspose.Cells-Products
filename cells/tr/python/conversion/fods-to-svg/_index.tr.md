---
title: Python'i kullanarak FODS'yi SVG'e dönüştürün
description:  FODS formatındaki bir dosyayı SVG formatındaki bir dosyaya dönüştürmek için Python için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert FODS to SVG, REST, Python
howto: How to convert FODS to SVG using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="FODS\'yi SVG\'e dönüştür" h2="FODS\'yi SVG\'e dönüştürmek için Python kütüphanesi" p="Python projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Python\'i kullanarak FODS\'yi SVG\'e ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/fods-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Python için Cells Cloud SDK\'yı kullanarak FODS\'yi SVG\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını FODS'den SVG'e dönüştürmek karmaşık bir iş olabilir. Python SDK'mız, kaynak FODS elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm FODS'den SVG formatına dönüşümleri gerçekleştirir. Python kitaplığımız, FODS'yi çevrimiçi olarak SVG dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Python geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli SVG çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Cells Cloud SDK\'yı kullanarak FODS\'yi SVG\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.fods",format="svg")
    shutil.move(file1, "destFile.svg")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Python kitaplığını kullanarak FODS\'yi SVG\'e nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Python kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Python'de açın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
