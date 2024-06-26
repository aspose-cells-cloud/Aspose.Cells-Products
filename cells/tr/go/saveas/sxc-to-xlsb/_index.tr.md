---
title:  Go'yu kullanarak SXC'yi XLSB olarak kaydedin
description:  SXC formatındaki dosyayı XLSB formatındaki dosya olarak kaydetmek için Go için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save SXC as XLSB, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save SXC as XLSB using the Cells Cloud Go library.","description": "How to save SXC as XLSB using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/sxc-to-xlsb/","step": [{ "@type": "HowToStep","name": "How to save SXC as XLSB using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/sxc-to-xlsb/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save SXC as XLSB using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/sxc-to-xlsb/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save SXC as XLSB using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/sxc-to-xlsb/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save SXC as XLSB using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/sxc-to-xlsb/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="SXC\'yi XLSB olarak kaydedin" h2="SXC\'yi XLSB olarak kaydetmek için kütüphaneye gidin" p="Go\'da özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API / Cells Cloud\'u kullanın. Bu, Go\'yu kullanarak SXC\'yi XLSB ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/sxc-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Go\'da bir SXC dosyasını XLSB olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını SXC'den XLSB olarak kaydetmek karmaşık bir iştir. SXC'den XLSB'ye tüm format geçişleri, kaynak SXC elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken Go SDK'mız tarafından gerçekleştirilir. Go kitaplığımız, SXC'yi çevrimiçi olarak XLSB dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Go geliştiricilerine güçlü işlevsellik ve mükemmel XLSB çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="REST API\'i kullanarak SXC\'yi XLSB olarak kaydetmek için Kod Örneğine gidin" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.sxc"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xlsb"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Go kitaplığını kullanarak SXC\'yi XLSB olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Go kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı go'da açın.</li>
<li>Ortaya çıkan akışı almak için `PostWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>go sürümü go1.13.0 veya daha yeni</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
