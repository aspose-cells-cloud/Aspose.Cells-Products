---
title:  Python'i kullanarak TXT'yi XLTM'ye dönüştürün
description:  TXT formatındaki bir dosyayı XLTM formatındaki bir dosyaya dönüştürmek için Python için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert TXT to XLTM, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert TXT to XLTM using the Cells Cloud Python library.","description": "How to convert TXT to XLTM using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/conversion/txt-to-xltm/","step": [{ "@type": "HowToStep","name": "How to convert TXT to XLTM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-xltm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert TXT to XLTM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-xltm/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert TXT to XLTM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-xltm/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to convert TXT to XLTM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-xltm/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="TXT\'yi XLTM\'ye dönüştür" h2="TXT\'yi XLTM\'ye dönüştürmek için Python kütüphane" p="Python projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Python\'i kullanarak TXT\'yi XLTM\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/txt-to-xltm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Python için Cells Cloud SDK\'yı kullanarak TXT\'yi XLTM\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını TXT'den XLTM'ye dönüştürmek karmaşık bir iş olabilir. Python SDK'mız, kaynak TXT elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm TXT'den XLTM formatına dönüşümleri gerçekleştirir. Python kitaplığımız, TXT'yi çevrimiçi olarak XLTM dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, Python geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli XLTM çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Cells Bulut SDK\'yı kullanarak TXT\'yi XLTM\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.txt",format="xltm")
    shutil.move(file1, "destFile.xltm")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Python kitaplığını kullanarak TXT\'yi XLTM\'ye dönüştürme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Python kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Python'de açın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
