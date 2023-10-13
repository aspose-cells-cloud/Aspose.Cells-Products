﻿---
title:  BMP'i XLSM'ye NodeJS için API'e Dönüştür
description:  BMP biçimindeki dosyayı XLSM biçimindeki dosyaya dönüştürmek için NodeJS için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/nodejs/conversion/bmp-to-xlsm/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="BMP\'i XLSM\'ye dönüştürmek için NodeJS API" h2="BMP\'i XLSM\'ye dönüştürmek için NodeJS kitaplığı" p="NodeJS\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, NodeJS kullanarak BMP\'i XLSM\'ye ve diğer belge biçimlerine çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/bmp-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="BMP dosyasını NodeJS\'de XLSM\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını BMP'den XLSM'ye dönüştürmek karmaşık bir iştir. Tüm BMP'den XLSM formatına geçişler, kaynak BMP e-tablosunun ana yapısal ve mantıksal içeriği korunurken NodeJS SDK'mız tarafından gerçekleştirilir. NodeJS kitaplığımız, BMP'i çevrimiçi olarak XLSM dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, NodeJS geliştiricilerine güçlü işlevsellik ve mükemmel XLSM çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="BMP\'i XLSM formatına dönüştürmek için REST API kullanan NodeJS\'deki kod örneği" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.bmp"),
        format: "xlsm",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="BMP\'i XLSM\'ye dönüştürmek için API Düğümü nasıl kullanılır?" >}}
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