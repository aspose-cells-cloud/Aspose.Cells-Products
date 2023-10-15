---
title: Python'i kullanarak XLSB'yi FODS olarak kaydedin
description:  XLSB formatındaki dosyayı FODS formatındaki dosya olarak kaydetmek için Python için Aspose.Cells Cloud SDK'yı kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSB\'yi FODS olarak kaydet" h2="XLSB\'yi FODS olarak kaydetmek için Python kütüphane" p="Python\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API\'ini Kaydet\'i kullanın. Bu, Python\'i kullanarak XLSB\'yi FODS ve diğer belge formatları olarak çevrimiçi kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xlsb-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir XLSB dosyasını Python\'e FODS olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını XLSB'den FODS olarak kaydetmek karmaşık bir iştir. Tüm XLSB'den FODS formatına geçişler, Python SDK'mız tarafından gerçekleştirilir ve kaynak XLSB elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. Python kitaplığımız, XLSB'yi çevrimiçi FODS dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Python geliştiriciye güçlü işlevsellik ve mükemmel FODS çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python REST API kullanarak XLSB\'yi FODS olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsb'    
    saveOptions = None
    newfilename = "Book1Saveas.fods"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer XLSB formatlarında FODS olarak kaydetmek için Python için Cells Cloud SDK nasıl kullanılır?" >}}
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
