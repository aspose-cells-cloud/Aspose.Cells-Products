---
title:  NUMBERS'ı Python'i kullanarak XLT olarak kaydedin
description:  NUMBERS biçimindeki dosyayı XLT biçimindeki dosya olarak kaydetmek için Python için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Save NUMBERS as XLT, REST, Python
howto: How to save NUMBERS as XLT using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="NUMBERS\'ı XLT olarak kaydet" h2="NUMBERS\'ı XLT olarak kaydetmek için Python kitaplık" p="Python\'de özelleştirilmiş e-tablo iş akışları oluşturmak için SaveAs Cells Cloud\'un API\'ini kullanın. Bu, NUMBERS\'ı Python\'i kullanarak çevrimiçi olarak XLT ve diğer belge formatları olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/numbers-to-xlt/" >}}

{{< blocks/products/cells/cells-cloud-section title="NUMBERS dosyasını Python\'e XLT olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
NUMBERS dosyasındaki dosya formatlarını XLT olarak kaydetmek karmaşık bir iştir. NUMBERS'tan XLT formatına tüm geçişler, Python SDK'mız tarafından gerçekleştirilir ve kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriği korunur. Python kitaplığımız, NUMBERS'ı çevrimiçi olarak XLT dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK'sı, Python geliştiriciye güçlü işlevsellik ve mükemmel XLT çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python REST API\'i kullanarak NUMBERS\'ı XLT olarak kaydetmeye yönelik Kod Örneği" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.numbers'    
    saveOptions = None
    newfilename = "Book1Saveas.xlt"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Bulut Python kitaplığını kullanarak NUMBERS\'ı XLT olarak nasıl kaydedeceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Python kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Python'de açın.</li>
<li>Ortaya çıkan akışı almak için `post_workbook_save_as` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
