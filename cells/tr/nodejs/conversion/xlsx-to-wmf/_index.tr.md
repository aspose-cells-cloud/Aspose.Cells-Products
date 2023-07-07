---
title:  NodeJS için XLSX'ten WMF'ye Dönüştürme API
description:  XLSX biçim dosyasını WMF biçim dosyasına dönüştürmek için NodeJS için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/nodejs/conversion/xlsx-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSX\'i WMF\'ye dönüştürmek için NodeJS API" h2="XLSX\'i WMF\'ye dönüştürmek için NodeJS kitaplığı" p="NodeJS\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, XLSX\'i NodeJS kullanarak çevrimiçi olarak WMF\'ye ve diğer belge biçimlerine dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xlsx-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir XLSX dosyasını NodeJS\'de WMF\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLSX'ten WMF'ye dönüştürmek karmaşık bir iştir. Tüm XLSX'ten WMF formatına geçişler, kaynak XLSX elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken NodeJS SDK'mız tarafından gerçekleştirilir. NodeJS kitaplığımız, XLSX'i çevrimiçi olarak WMF dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, NodeJS geliştiricilerine güçlü işlevsellik ve mükemmel WMF çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="XLSX\'i WMF formatına dönüştürmek için REST API kullanan NodeJS\'deki kod örneği" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xlsx"),
        format: "wmf",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="XLSX\'i WMF\'ye dönüştürmek için Düğüm API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için cellsWorkbookPutConvertWorkbook yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>düğüm v6.17.1 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
