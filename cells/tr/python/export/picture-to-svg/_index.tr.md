---
title: Python için Cells Bulut SDK'sını kullanarak RESMİ Excel'den SVG'e aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="RESMİ Excel\'den SVG\'e aktar" h2="RESİM\'i SVG dosyasına aktarmak için Python kitaplığı" p="Python\'de Excel dosya dahili nesne iş akışlarını dışa aktarmak için Cells Bulut\'un API\'ini Dışa Aktar\'ı kullanın. Bu, Python\'i kullanarak çevrimiçi tablodan RESİM\'i SVG biçimindeki dosyaya dışa aktarmak için profesyonel bir çözümdür." urlsection="export/picture-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Python için Cells Bulut SDK\'sını kullanarak PICTURE nesnesini SVG biçim dosyasına aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
PICTURE nesnesini Excel dosyasından SVG dosyasına aktarmak karmaşık bir iştir. PICTURE'ı SVG'e aktar format geçişleri Python SDK'mız tarafından gerçekleştirilir ve kaynak PICTURE elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. Python kitaplığımız, RESİM nesnelerini çevrimiçi olarak SVG formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK, Python geliştiriciye güçlü işlevsellik ve mükemmel SVG çıktı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="RESİM\'i e-tablodan SVG formatına aktarmak için REST API\'i kullanan Python\'deki kod örneği" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import base64
    from asposecellscloud.apis.light_cells_api import LightCellsApi
    cells_api = LightCellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    files ={ 
        "myDocument.xlsx" :  "c:/myDocument.xlsx",
        "Book1.xlsx" :  "c:/Book1.xlsx" 
        }
    result = cells_api.post_export(files ,"picture","svg")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel PICTURE\'dan SVG\'e nesneleri dışa aktarmak için Python için Cells Cloud SDK nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için post_export yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
