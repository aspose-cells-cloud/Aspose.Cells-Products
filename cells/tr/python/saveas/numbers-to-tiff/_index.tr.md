---
title:  NUMARALARI Python'i kullanarak TIFF olarak kaydedin
description:  NUMBERS biçimindeki dosyayı TIFF biçimindeki dosya olarak kaydetmek için Python için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Save NUMBERS as TIFF, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save NUMBERS as TIFF using the Cells Cloud Python library.","description": "How to save NUMBERS as TIFF using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/numbers-to-tiff/","step": [{ "@type": "HowToStep","name": "How to save NUMBERS as TIFF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/numbers-to-tiff/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save NUMBERS as TIFF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/numbers-to-tiff/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save NUMBERS as TIFF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/numbers-to-tiff/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save NUMBERS as TIFF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/numbers-to-tiff/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="NUMBERS\'ı TIFF olarak kaydet" h2="NUMARALARI TIFF olarak kaydetmek için Python kitaplığı" p="Python\'de özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulut\'un API\'ini Kaydet\'i kullanın. Bu, NUMBERS\'ı TIFF olarak ve Python\'i kullanarak diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/numbers-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="NUMBERS dosyasını Python\'e TIFF olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
NUMBERS'tan dosya formatlarını TIFF olarak kaydetmek karmaşık bir iştir. NUMBERS'tan TIFF'e tüm format geçişleri, kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriği korunurken Python SDK'mız tarafından gerçekleştirilir. Python kitaplığımız, NUMARALARI çevrimiçi olarak TIFF dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Python geliştiricilerine güçlü işlevsellik ve mükemmel TIFF çıktı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python NUMARALARI REST API kullanarak TIFF olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.numbers'    
    saveOptions = None
    newfilename = "Book1Saveas.tiff"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Python kitaplığını kullanarak NUMBERS\'ı TIFF olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Python kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Python'de açın.</li>
<li>Ortaya çıkan akışı almak için `post_workbook_save_as` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
