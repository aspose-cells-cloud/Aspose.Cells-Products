﻿---
title: TXT'yi Python için ODS API olarak kaydedin
description:  TXT biçim dosyasını ODS biçim dosyası olarak kaydetmek için Python için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/python/saveas/txt-to-ods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="TXT\'yi ODS olarak kaydetmek için Python API" h2="TXT\'yi ODS olarak kaydetmek için Python kitaplığı" p="Python\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, Python\'i kullanarak TXT\'yi ODS ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/txt-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir TXT dosyasını Python\'de ODS olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya biçimlerini TXT'den ODS olarak kaydetmek karmaşık bir iştir. Tüm TXT - ODS biçim geçişleri, kaynak TXT e-tablosunun ana yapısal ve mantıksal içeriği korunurken Python SDK'mız tarafından gerçekleştirilir. Python kitaplığımız, TXT'yi çevrimiçi ODS dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Cloud SDK, Python geliştiricilerine güçlü işlevsellik ve mükemmel ODS çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="TXT\'yi ODS formatı olarak kaydetmek için REST API\'i kullanan Python\'deki kod örneği" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.txt'    
    saveOptions = None
    newfilename = "Book1Saveas.ods"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="TXT\'yi ODS olarak kaydetmek için Python API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Çağrı hücreleri_kaydetmek_gibi_postalamak_belge_kaydetmek_sonuçtaki akışı alma yöntemi olarak</li>
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