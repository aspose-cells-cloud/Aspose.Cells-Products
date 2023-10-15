---
title:  NUMBERS'ı Python'i kullanarak MD olarak kaydedin
description:  NUMBERS biçimindeki dosyayı MD biçimindeki dosya olarak kaydetmek için Python için Aspose.Cells Bulut SDK'sını kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NUMBERS\'ı MD olarak kaydet" h2="NUMBERS\'ı MD olarak kaydetmek için Python kitaplığı" p="Python\'de özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulut\'un API\'i Kaydet\'i kullanın. Bu, Python\'i kullanarak NUMBERS\'ı MD ve diğer belge formatları olarak çevrimiçi kaydetmek için profesyonel bir çözümdür." urlsection="saveas/numbers-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="NUMBERS dosyasını Python\'e MD olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
NUMBERS dosyasındaki dosya formatlarını MD olarak kaydetmek karmaşık bir iştir. NUMBERS'tan MD formatına tüm geçişler, kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriği korunurken Python SDK'mız tarafından gerçekleştirilir. Python kitaplığımız, NUMBERS'ı çevrimiçi olarak MD dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Python geliştiriciye güçlü işlevsellik ve mükemmel MD çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python NUMBERS\'ı REST API kullanarak MD olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.numbers'    
    saveOptions = None
    newfilename = "Book1Saveas.md"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını MD olarak NUMBERS diğer formatlarda kaydetmek için Python için Cells Bulut SDK\'sı nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `post_workbook_save_as` yöntemini kullanın.</li>
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
