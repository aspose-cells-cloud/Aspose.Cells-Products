---
title:  PNG'i C#'i kullanarak TSV olarak kaydedin
description:  PNG formatındaki dosyayı TSV formatındaki dosya olarak kaydetmek için C# için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save PNG as TSV, REST, C#
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save PNG as TSV using the Cells Cloud Net library.","description": "How to save PNG as TSV using the Cells Cloud Net library.","image": {"@type": "ImageObject"},"url": "/net/saveas/png-to-tsv/","step": [{ "@type": "HowToStep","name": "How to save PNG as TSV using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/png-to-tsv/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save PNG as TSV using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/png-to-tsv/","text": "Install C# library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save PNG as TSV using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/png-to-tsv/","text": "Open the source file in C#",},{ "@type": "HowToStep","name": "How to save PNG as TSV using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/png-to-tsv/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="PNG\'i TSV olarak kaydet" h2="PNG\'i TSV olarak kaydetmek için C# kütüphanesi" p="Net\'te özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API / Cells Cloud\'u kullanın. Bu, PNG\'i TSV olarak ve C#\'i kullanarak çevrimiçi olarak diğer belge formatlarını kaydetmek için profesyonel bir çözümdür." urlsection="saveas/png-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="PNG dosyasını C#\'de TSV olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
PNG'den dosya formatlarını TSV olarak kaydetmek karmaşık bir iştir. PNG'den TSV formatına tüm geçişler, C# SDK'mız tarafından gerçekleştirilir ve kaynak PNG elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. C# kitaplığımız, PNG'i çevrimiçi olarak TSV dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, C# geliştiriciye güçlü işlevsellik ve mükemmel TSV çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# REST API kullanarak PNG\'i TSV olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.png";
    string newfilename = "Book1SaveAs.tsv";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Net kitaplığını kullanarak PNG\'i TSV olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>C# kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı C#'de açın</li>
<li>Ortaya çıkan akışı almak için `PostWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standardı 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
