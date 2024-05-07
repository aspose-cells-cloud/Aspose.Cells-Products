---
title:  NodeJS kullanarak XLSM'yi HTML olarak kaydedin
description:  XLSM formatındaki dosyayı HTML formatındaki dosya olarak kaydetmek için NodeJS için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save XLSM as HTML, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSM as HTML using the Cells Cloud NodeJS library.","description": "How to save XLSM as HTML using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/saveas/xlsm-to-html/","step": [{ "@type": "HowToStep","name": "How to save XLSM as HTML using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xlsm-to-html/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSM as HTML using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xlsm-to-html/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSM as HTML using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xlsm-to-html/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to save XLSM as HTML using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xlsm-to-html/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLSM\'yi HTML olarak kaydet" h2="XLSM\'yi HTML olarak kaydetmek için NodeJS kütüphanesi" p="NodeJS\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API of Cells Cloud\'u kullanın. Bu, XLSM\'yi HTML olarak ve diğer belge formatlarını NodeJS kullanarak çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xlsm-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Bir XLSM dosyasını NodeJS\'de HTML olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını XLSM'den HTML olarak kaydetmek karmaşık bir iştir. Tüm XLSM'den HTML'e format geçişleri, kaynak XLSM elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken NodeJS SDK'mız tarafından gerçekleştirilir. NodeJS kitaplığımız, XLSM'yi çevrimiçi olarak HTML dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, NodeJS geliştiricilerine güçlü işlevsellik ve mükemmel HTML çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="REST API\'i kullanarak XLSM\'yi HTML olarak kaydetmek için NodeJS Kod Örneği" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xlsm",
      folder: "CellsTests",
      newfilename: "Book1Saveas.html",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud NodeJS kitaplığını kullanarak XLSM\'yi HTML olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>NodeJS kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı JavaScript'te açın.</li>
<li>Ortaya çıkan akışı almak için `PostWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>düğüm v6.17.1 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
