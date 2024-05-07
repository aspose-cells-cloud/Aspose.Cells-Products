---
title:  Java'i kullanarak TXT'yi PPTX olarak kaydedin
description:  TXT formatındaki dosyayı PPTX formatındaki dosya olarak kaydetmek için Aspose.Cells Cloud SDK for Java'i kullanma.
kwords: Excel, Save TXT as PPTX, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save TXT as PPTX using the Cells Cloud Java library.","description": "How to save TXT as PPTX using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/txt-to-pptx/","step": [{ "@type": "HowToStep","name": "How to save TXT as PPTX using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/txt-to-pptx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save TXT as PPTX using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/txt-to-pptx/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save TXT as PPTX using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/txt-to-pptx/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save TXT as PPTX using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/txt-to-pptx/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="TXT\'yi PPTX olarak kaydedin" h2="TXT\'yi PPTX olarak kaydetmek için Java kitaplığı" p="Java\'de özelleştirilmiş e-tablo iş akışları oluşturmak için SaveAs API / Cells Cloud\'u kullanın. Bu, Java\'i kullanarak TXT\'yi PPTX ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/txt-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Bir TXT dosyasını Java\'e PPTX olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını TXT'den PPTX olarak kaydetmek karmaşık bir iştir. Tüm TXT'den PPTX'e format geçişleri, kaynak TXT elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken Java SDK'mız tarafından gerçekleştirilir. Java kitaplığımız, TXT'yi çevrimiçi PPTX dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Java geliştiriciye güçlü işlevsellik ve mükemmel PPTX çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java REST API kullanarak TXT\'yi PPTX olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.txt";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.pptx";
    String folder ="CellsTests";
    try 
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Java kitaplığını kullanarak TXT\'yi PPTX olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Java kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Java'de açın.</li>
<li>Ortaya çıkan akışı almak için `postWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Maven 2.2.0 veya daha yenisi</li>
<li>Java(TM) SE Çalışma Zamanı Ortamı</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
