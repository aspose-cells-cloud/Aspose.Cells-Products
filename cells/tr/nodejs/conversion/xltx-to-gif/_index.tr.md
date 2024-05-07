---
title:  NodeJS kullanarak XLTX'i GIF'e dönüştürün
description:  XLTX formatındaki bir dosyayı GIF formatındaki bir dosyaya dönüştürmek için NodeJS için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert XLTX to GIF, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLTX to GIF using the Cells Cloud NodeJS library.","description": "How to convert XLTX to GIF using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/conversion/xltx-to-gif/","step": [{ "@type": "HowToStep","name": "How to convert XLTX to GIF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xltx-to-gif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLTX to GIF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xltx-to-gif/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLTX to GIF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xltx-to-gif/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to convert XLTX to GIF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xltx-to-gif/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLTX\'i GIF\'ye dönüştür" h2="XLTX\'i GIF\'e dönüştürmek için NodeJS kütüphanesi" p="NodeJS projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, NodeJS\'yi kullanarak XLTX\'i çevrimiçi olarak GIF\'e ve diğer belge formatlarına dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xltx-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="NodeJS için Cells Cloud SDK\'yı kullanarak XLTX\'i GIF\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLTX'ten GIF'e dönüştürmek karmaşık bir iş olabilir. NodeJS SDK'mız, kaynak XLTX elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm XLTX'ten GIF formatına dönüşümleri gerçekleştirir. NodeJS kitaplığımız, XLTX'i çevrimiçi olarak GIF dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, NodeJS geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli GIF çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Cells Cloud SDK\'yı kullanarak XLTX\'i GIF\'e dönüştürmek için NodeJS Kod Örneği" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xltx"),
        format: "gif",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud NodeJS kitaplığını kullanarak XLTX\'i GIF\'e dönüştürme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>NodeJS kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı JavaScript'te açın.</li>
<li>Ortaya çıkan akışı almak için `putConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>düğüm v6.17.1 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
