﻿---
title:  NodeJS API kullanarak ÇALIŞMA KİTABI'nı e-tablodan CSV'ye aktarın
description:  Aspose.Cells Cloud REST API, {0} dosyalarını {2} kullanarak {1} biçiminde dışa aktarmayı destekler.
url: /tr/nodejs/export/workbook-to-csv/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="ÇALIŞMA KİTABI\'nı CSV dosyasına dışa aktarmak için NodeJS API" h2="ÇALIŞMA KİTABI\'nı CSV dosyasına aktarmak için NodeJS kitaplığı" p="NodeJS\'de elektronik tablo dahili nesne iş akışlarını dışa aktarmak için Cells Export REST API\'i kullanın. Bu, NodeJS kullanarak ÇALIŞMA KİTABI\'nı e-tablodan CSV formatında dosyaya aktarmak için profesyonel bir çözümdür." urlsection="export/workbook-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="WORKBOOK nesnesini NodeJS\'de CSV formatındaki dosyaya aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
ÇALIŞMA KİTABI nesnesini e-tablodan CSV dosyasına aktarma karmaşık bir görevdir. WORKBOOK'u CSV biçimine dışa aktarma geçişleri, kaynak WORKBOOK elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken NodeJS SDK'mız tarafından gerçekleştirilir. NodeJS kitaplığımız, WORKBOOK nesnelerini çevrimiçi olarak CSV formatındaki dosyalara dışa aktarmak için profesyonel bir çözümdür. Bu Cloud SDK, NodeJS geliştiricilerine güçlü işlevsellik ve mükemmel CSV çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="ÇALIŞMA KİTABI\'nı e-tablodan CSV formatına dışa aktarmak için REST API kullanan NodeJS\'deki kod örneği" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { LightCellsApi, PostExportRequest } = require("asposecellscloud");
    const localPath = "C:/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new LightCellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    const AssemblyTestXlsx = "assemblytest.xlsx";
    var dataAssemblyTestXlsx =fs.createReadStream(localPath  + AssemblyTestXlsx);
    const DataSourceXlsx = "datasource.xlsx";
    var dataDataSourceXlsx =fs.createReadStream(localPath  + DataSourceXlsx);
    var req = new PostExportRequest({
      file:{AssemblyTestXlsx:dataAssemblyTestXlsx ,DataSourceXlsx:dataDataSourceXlsx },
      objectType : "workbook",
      format: "csv",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="ÇALIŞMA KİTABI\'nı CSV\'ye dışa aktarmak için Düğüm API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için postExport yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>düğüm v6.17.1 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}