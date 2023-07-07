---
title:  XLT'yi NodeJS için XLS API olarak kaydedin
description: XLT biçim dosyasını XLS biçim dosyası olarak kaydetmek için NodeJS için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/nodejs/saveas/xlt-to-xls/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLT\'yi XLS olarak kaydetmek için NodeJS API" h2="XLT\'yi XLS olarak kaydetmek için NodeJS kitaplığı" p="NodeJS\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, XLT\'yi NodeJS kullanarak çevrimiçi olarak XLS ve diğer belge biçimleri olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xlt-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir XLT dosyasını NodeJS\'de XLS olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya biçimlerini XLT'den XLS olarak kaydetmek karmaşık bir görevdir. Tüm XLT'den XLS'ye biçim geçişleri, kaynak XLT e-tablosunun ana yapısal ve mantıksal içeriğini korurken NodeJS SDK'mız tarafından gerçekleştirilir. NodeJS kitaplığımız, XLT'yi çevrimiçi olarak XLS dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Cloud SDK, NodeJS geliştiricilerine güçlü işlevsellik ve mükemmel XLS çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="XLT\'yi XLS formatı olarak kaydetmek için REST API kullanan NodeJS\'deki kod örneği" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xlt",
      folder: "CellsTests",
      newfilename: "Book1Saveas.xls",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="XLT\'yi XLS olarak kaydetmek için API Düğümü nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için cellSaveAsPostDocumentSaveAs yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>düğüm v6.17.1 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
