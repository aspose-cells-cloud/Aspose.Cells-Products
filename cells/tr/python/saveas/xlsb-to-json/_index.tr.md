---
title:  Python'i kullanarak XLSB'yi JSON olarak kaydedin
description:  XLSB formatındaki dosyayı JSON formatındaki dosya olarak kaydetmek için Python için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save XLSB as JSON, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSB as JSON using the Cells Cloud Python library.","description": "How to save XLSB as JSON using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/xlsb-to-json/","step": [{ "@type": "HowToStep","name": "How to save XLSB as JSON using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsb-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSB as JSON using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsb-to-json/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSB as JSON using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsb-to-json/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save XLSB as JSON using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsb-to-json/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLSB\'yi JSON olarak kaydet" h2="XLSB\'yi JSON olarak kaydetmek için Python kitaplığı" p="Python\'de özelleştirilmiş e-tablo iş akışları oluşturmak için SaveAs API / Cells Cloud\'u kullanın. Bu, Python\'i kullanarak XLSB\'yi JSON ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xlsb-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Bir XLSB dosyasını Python\'e JSON olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını XLSB'den JSON olarak kaydetmek karmaşık bir iştir. Tüm XLSB'den JSON formatına geçişler, Python SDK'mız tarafından gerçekleştirilir ve kaynak XLSB elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. Python kitaplığımız, XLSB'yi çevrimiçi JSON dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK'sı, Python geliştiriciye güçlü işlevsellik ve mükemmel JSON çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python XLSB\'yi REST API kullanarak JSON olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsb'    
    saveOptions = None
    newfilename = "Book1Saveas.json"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Python kitaplığını kullanarak XLSB\'yi JSON olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Python kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Python'de açın.</li>
<li>Ortaya çıkan akışı almak için `post_workbook_save_as` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
