---
title:  Python için Cells Cloud SDK'yı kullanarak LISTOBJECT'i Excel'den DOCX'e aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
kwords: Excel, listobject, docx, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to DOCX","description": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to DOCX","image": {"@type": "ImageObject"},"url": "/python/export/listobject-to-docx/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to DOCX step 1", "image": {"@type": "ImageObject",},"url": "/python/export/listobject-to-docx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to DOCX step 1", "image": {"@type": "ImageObject",},"url": "/python/export/listobject-to-docx/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to DOCX step 1", "image": {"@type": "ImageObject",},"url": "/python/export/listobject-to-docx/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="LISTOBJECT\'i Excel\'den DOCX\'e aktar" h2="LISTOBJECT\'i DOCX dosyasına aktarmak için Python kitaplığı" p="Python\'de Excel dosya dahili nesne iş akışlarını dışa aktarmak için Cells Bulut\'un API\'ini Dışa Aktar\'ı kullanın. Bu, Python\'i kullanarak elektronik tablodan LISTOBJECT\'i DOCX biçimindeki dosyaya çevrimiçi olarak dışa aktarmak için profesyonel bir çözümdür." urlsection="export/listobject-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Python için Cells Cloud SDK\'yı kullanarak LISTOBJECT nesnesini DOCX biçimindeki dosyaya aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
LISTOBJECT nesnesini Excel dosyasından DOCX dosyasına aktarmak karmaşık bir iştir. LISTOBJECT'i DOCX formatına dışa aktarma, kaynak LISTOBJECT elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken Python SDK'mız tarafından gerçekleştirilir. Python kitaplığımız, LISTOBJECT nesnelerini çevrimiçi olarak DOCX formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK'sı, Python geliştiriciye güçlü işlevsellik ve mükemmel DOCX çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="LISTOBJECT\'i elektronik tablodan DOCX formatına aktarmak için REST API\'i kullanan Python\'deki kod örneği" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"listobject","docx")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Nesneleri Excel LISTOBJECT\'ten DOCX\'e aktarmak için Python için Cells Bulut SDK\'sı nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için post_export yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Python 2.7 veya daha yenisi</li>
<li>Python 3.10 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
