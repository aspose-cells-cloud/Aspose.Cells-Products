﻿---
title:  Swift API kullanarak CHART'ı e-tablodan PDF'e aktarın
description:  Aspose.Cells Cloud REST API, {0} dosyalarını {2} kullanarak {1} biçiminde dışa aktarmayı destekler.
url: /tr/swift/export/chart-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="CHART\'ı PDF dosyasına dışa aktarmak için Swift API" h2="CHART\'ı PDF dosyasına dışa aktarmak için Swift kitaplığı" p="Swift\'de elektronik tablo dahili nesne iş akışlarını dışa aktarmak için Cells Export REST API\'i kullanın. Bu, Swift kullanarak elektronik tablodan CHART\'ı PDF biçimindeki dosyaya dışa aktarmak için profesyonel bir çözümdür." urlsection="export/chart-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="CHART nesnesini Swift\'de PDF biçim dosyasına aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
CHART nesnesini elektronik tablodan PDF dosyasına dışa aktarma karmaşık bir iştir. CHART'ı PDF biçimine dışa aktarma geçişleri, kaynak CHART e-tablosunun ana yapısal ve mantıksal içeriğini korurken Swift SDK'mız tarafından gerçekleştirilir. Swift kitaplığımız, CHART nesnelerini çevrimiçi olarak PDF biçimindeki dosyalara dışa aktarmak için profesyonel bir çözümdür. Bu Cloud SDK, Swift geliştiricilerine güçlü işlevsellik ve mükemmel PDF çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="CHART\'ı e-tablodan PDF biçimine dışa aktarmak için REST API kullanan Swift kod örneği" gistPath="" %}}
  
```swift
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-swift/
    import AsposeCellsCloud
    let expectation1 = self.expectation(description: "checkAuth")
    AsposeCellsCloudAPI.clientId = "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"
    AsposeCellsCloudAPI.clientSecret = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
    AuthAspose.checkAuth()
    {
        (authError) in
        guard authError == nil else {
            XCTFail("error checkAuth")
            return
        }
        expectation1.fulfill()
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
    let expectation = self.expectation(description: "testpostExport_Workbook")
    let objectType:String = "chart"
    let format:String = "pdf"
    var files = Dictionary<String, URL>()
    files[BOOK1] = getURL(BOOK1)
    files[MYDOC] = getURL(MYDOC)        
    LiteCellsAPI.postExport(files: files, objectType: objectType, format: format)
    {
        (response, error) in
        guard error == nil else {
            XCTFail("error testpostExport_Workbook")
            return
        }        
        if let response = response {
            XCTAssertTrue(response is FilesResult)
            expectation.fulfill()
        }
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="CHART\'ı PDF\'e dışa aktarmak için Swift API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için postExport yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}