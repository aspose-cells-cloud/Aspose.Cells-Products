﻿---
title: Python API kullanarak WORKSHEET'i elektronik tablodan TXT'ye aktarın
description:  Aspose.Cells Cloud REST API, {0} dosyalarını {2} kullanarak {1} biçiminde dışa aktarmayı destekler.
url: /tr/python/export/worksheet-to-txt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API, WORKSHEET\'i TXT dosyasına aktarmak için" h2="WORKSHEET\'i TXT dosyasına dışa aktarmak için Python kitaplığı" p="Python\'deki elektronik tablo dahili nesne iş akışlarını dışa aktarmak için Cells Export REST API\'i kullanın. Bu, Python kullanarak çevrimiçi elektronik tablodan WORKSHEET\'i TXT biçimindeki dosyaya dışa aktarmak için profesyonel bir çözümdür." urlsection="export/worksheet-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="WORKSHEET nesnesini Python\'de TXT format dosyasına aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
WORKSHEET nesnesini elektronik tablodan TXT dosyasına aktarma karmaşık bir görevdir. WORKSHEET'i TXT formatına aktarma geçişleri, kaynak WORKSHEET e-tablosunun ana yapısal ve mantıksal içeriği korunurken Python SDK'mız tarafından gerçekleştirilir. Python kitaplığımız, WORKSHEET nesnelerini çevrimiçi olarak TXT biçimindeki dosyalara dışa aktarmak için profesyonel bir çözümdür. Bu Cloud SDK, Python geliştiricilerine güçlü işlevsellik ve mükemmel TXT çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="WORKSHEET\'i elektronik tablodan TXT biçimine aktarmak için REST API kullanan Python\'deki kod örneği" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"worksheet","txt")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="WORKSHEET\'i TXT\'ye dışa aktarmak için Python API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için post_export yöntemini çağırın</li>
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