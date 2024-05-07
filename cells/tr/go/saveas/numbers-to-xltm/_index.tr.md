---
title:  NUMBERS'ı Go'yu kullanarak XLTM olarak kaydedin
description:  NUMBERS biçimindeki dosyayı XLTM biçimindeki dosya olarak kaydetmek için Go için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save NUMBERS as XLTM, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save NUMBERS as XLTM using the Cells Cloud Go library.","description": "How to save NUMBERS as XLTM using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/numbers-to-xltm/","step": [{ "@type": "HowToStep","name": "How to save NUMBERS as XLTM using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/numbers-to-xltm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save NUMBERS as XLTM using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/numbers-to-xltm/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save NUMBERS as XLTM using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/numbers-to-xltm/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save NUMBERS as XLTM using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/numbers-to-xltm/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="NUMBERS\'ı XLTM olarak kaydet" h2="NUMBERS\'ı XLTM olarak kaydetmek için kitaplığa gidin" p="Go\'da özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API / Cells Cloud\'u kullanın. Bu, Go\'yu kullanarak NUMBERS\'ı XLTM ve diğer belge formatlarında çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/numbers-to-xltm/" >}}

{{< blocks/products/cells/cells-cloud-section title="NUMBERS dosyasını Go\'da XLTM olarak kaydetme" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
NUMBERS dosyasındaki dosya formatlarını XLTM olarak kaydetmek karmaşık bir iştir. NUMBERS'tan XLTM'ye tüm format geçişleri, kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriği korunurken Go SDK'mız tarafından gerçekleştirilir. Go kitaplığımız, NUMBERS'ı çevrimiçi olarak XLTM dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Go geliştiricilerine güçlü işlevsellik ve mükemmel XLTM çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="REST API\'i kullanarak NUMBERS\'ı XLTM olarak kaydetmek için Kod Örneğine gidin" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.numbers"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xltm"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Go kitaplığını kullanarak NUMBERS\'ı XLTM olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Go kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı go'da açın.</li>
<li>Ortaya çıkan akışı almak için `PostWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>go sürümü go1.13.0 veya daha yeni</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
