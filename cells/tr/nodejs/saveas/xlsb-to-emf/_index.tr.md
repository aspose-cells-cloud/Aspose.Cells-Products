﻿---
title:  NodeJS için XLSB'yi EMF API olarak kaydedin
description: XLSB biçim dosyasını EMF biçim dosyası olarak kaydetmek için NodeJS için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/nodejs/saveas/xlsb-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSB\'yi EMF olarak kaydetmek için NodeJS API" h2="XLSB\'yi EMF olarak kaydetmek için NodeJS kitaplığı" p="NodeJS\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, XLSB\'yi EMF olarak ve diğer belge biçimlerini NodeJS kullanarak çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xlsb-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir XLSB dosyasını NodeJS\'de EMF olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını XLSB'den EMF olarak kaydetmek karmaşık bir iştir. Tüm XLSB - EMF biçim geçişleri, kaynak XLSB e-tablosunun ana yapısal ve mantıksal içeriği korunurken NodeJS SDK'mız tarafından gerçekleştirilir. NodeJS kitaplığımız, XLSB'yi çevrimiçi olarak EMF dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Cloud SDK, NodeJS geliştiricilerine güçlü işlevsellik ve mükemmel EMF çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="XLSB\'yi EMF biçiminde kaydetmek için REST API kullanan NodeJS\'deki kod örneği" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xlsb",
      folder: "CellsTests",
      newfilename: "Book1Saveas.emf",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="XLSB\'yi EMF olarak kaydetmek için API Düğümü nasıl kullanılır?" >}}
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