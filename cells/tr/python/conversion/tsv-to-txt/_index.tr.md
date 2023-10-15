---
title:  Python'i kullanarak TSV'yi TXT'ye dönüştürün
description:  TSV formatındaki bir dosyayı TXT formatındaki bir dosyaya dönüştürmek için Python için Aspose.Cells Cloud SDK'yı kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="TSV\'yi TXT\'ye dönüştür" h2="TSV\'yi TXT\'ye dönüştürmek için Python kitaplığı" p="Python projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Python\'i kullanarak TSV\'yi TXT\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/tsv-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Python için Cells Cloud SDK\'yı kullanarak TSV\'yi TXT\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını TSV'den TXT'ye dönüştürmek karmaşık bir iş olabilir. Python SDK'mız, kaynak TSV e-tablosunun ana yapısal ve mantıksal içeriğini korurken tüm TSV'den TXT formatına dönüşümleri gerçekleştirir. Python kitaplığımız, TSV'yi çevrimiçi olarak TXT dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Python geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli TXT çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Cells Bulut SDK\'yı kullanarak TSV\'yi TXT\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.tsv",format="txt")
    shutil.move(file1, "destFile.txt")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer formatlara TSV\'den TXT\'ye dönüştürmek için Python için Cells Cloud SDK nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
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
