---
title:  NodeJS kullanarak XLTM'yi ODS olarak kaydedin
description:  XLTM formatındaki dosyayı ODS formatındaki dosya olarak kaydetmek için NodeJS için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save XLTM as ODS, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLTM as ODS using the Cells Cloud NodeJS library.","description": "How to save XLTM as ODS using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/saveas/xltm-to-ods/","step": [{ "@type": "HowToStep","name": "How to save XLTM as ODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xltm-to-ods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLTM as ODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xltm-to-ods/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLTM as ODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xltm-to-ods/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to save XLTM as ODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xltm-to-ods/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLTM\'yi ODS olarak kaydet" h2="XLTM\'yi ODS olarak kaydetmek için NodeJS kütüphanesi" p="NodeJS\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API of Cells Cloud\'u kullanın. Bu, NodeJS kullanarak XLTM\'yi ODS ve diğer belge formatları olarak çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xltm-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Bir XLTM dosyasını NodeJS\'de ODS olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını XLTM'den ODS olarak kaydetmek karmaşık bir iştir. XLTM'den ODS formatına tüm geçişler, kaynak XLTM elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken NodeJS SDK'mız tarafından gerçekleştirilir. NodeJS kitaplığımız, XLTM'yi çevrimiçi ODS dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, NodeJS geliştiricilerine güçlü işlevsellik ve mükemmel ODS çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="REST API\'i kullanarak XLTM\'yi ODS olarak kaydetmek için NodeJS Kod Örneği" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xltm",
      folder: "CellsTests",
      newfilename: "Book1Saveas.ods",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud NodeJS kitaplığını kullanarak XLTM\'yi ODS olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>NodeJS kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı JavaScript'te açın.</li>
<li>Ortaya çıkan akışı almak için `PostWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>düğüm v6.17.1 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
