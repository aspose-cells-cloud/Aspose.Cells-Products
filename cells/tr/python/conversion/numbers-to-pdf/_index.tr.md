---
title:  Python'i kullanarak NUMBERS'ı PDF'e dönüştürün
description:  NUMBERS biçimindeki bir dosyayı PDF biçimindeki bir dosyaya dönüştürmek için Python için Aspose.Cells Bulut SDK'sını kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NUMBERS\'ı PDF\'e dönüştür" h2="NUMBERS\'ı PDF\'e dönüştürmek için Python kitaplığı" p="Python projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, NUMBERS\'ı PDF\'e ve Python\'i kullanarak çevrimiçi olarak diğer belge formatlarına dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/numbers-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Python için Cells Cloud SDK\'yı kullanarak NUMBERS\'ı PDF\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını NUMBERS'tan PDF'e dönüştürmek karmaşık bir iş olabilir. Python SDK'mız, kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm NUMBERS'dan PDF'e format dönüşümlerini gerçekleştirir. Python kitaplığımız, NUMBERS'ı çevrimiçi olarak PDF dosyalara dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Python geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli PDF çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python NUMBERS\'ı Cells Cloud SDK kullanarak PDF\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.numbers",format="pdf")
    shutil.move(file1, "destFile.pdf")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını NUMBERS ile PDF arasındaki diğer formatlara dönüştürmek için Python için Cells Cloud SDK nasıl kullanılır?" >}}
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
