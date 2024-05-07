---
title:  C#'i kullanarak TSV'yi TXT olarak kaydedin
description:  TSV formatındaki dosyayı TXT formatındaki dosya olarak kaydetmek için C# için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save TSV as TXT, REST, C#
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save TSV as TXT using the Cells Cloud Net library.","description": "How to save TSV as TXT using the Cells Cloud Net library.","image": {"@type": "ImageObject"},"url": "/net/saveas/tsv-to-txt/","step": [{ "@type": "HowToStep","name": "How to save TSV as TXT using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/tsv-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save TSV as TXT using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/tsv-to-txt/","text": "Install C# library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save TSV as TXT using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/tsv-to-txt/","text": "Open the source file in C#",},{ "@type": "HowToStep","name": "How to save TSV as TXT using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/tsv-to-txt/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="TSV\'yi TXT olarak kaydet" h2="TSV\'yi TXT olarak kaydetmek için C# kitaplığı" p="Net\'te özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API / Cells Cloud\'u kullanın. Bu, C#\'i kullanarak TSV\'yi TXT ve diğer belge formatlarında çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/tsv-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Bir TSV dosyasını C#\'e TXT olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını TSV'den TXT olarak kaydetmek karmaşık bir iştir. TSV'den TXT'ye tüm format geçişleri, kaynak TSV elektronik tablosunun ana yapısal ve mantıksal içeriği korunarak C# SDK'mız tarafından gerçekleştirilir. C# kitaplığımız, TSV'yi çevrimiçi TXT dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, C# geliştiriciye güçlü işlevsellik ve mükemmel TXT çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# REST API kullanarak TSV\'yi TXT olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.tsv";
    string newfilename = "Book1SaveAs.txt";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Net kitaplığını kullanarak TSV\'yi TXT olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>C# kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı C#'de açın</li>
<li>Ortaya çıkan akışı almak için `PostWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standardı 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
