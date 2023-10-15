---
title:  Swift API kullanarak çalışma kitabını e-tablodan PNG'e aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
url: /tr/swift/export/workbook-to-png/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="ÇALIŞMA KİTABINI PNG dosyasına aktarmak için Swift API" h2="ÇALIŞMA KİTABI\'nı PNG dosyasına aktarmak için Swift kütüphanesi" p="Swift\'de elektronik tablo dahili nesne iş akışlarını dışa aktarmak için Cells REST\'i Dışa Aktar API\'i kullanın. Bu, Swift kullanarak çevrimiçi elektronik tablodan ÇALIŞMA KİTABI\'nı PNG formatındaki dosyaya aktarmak için profesyonel bir çözümdür." urlsection="export/workbook-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="ÇALIŞMA KİTABI nesnesini Swift\'de PNG formatındaki dosyaya aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
ÇALIŞMA KİTABI nesnesini e-tablodan PNG dosyasına aktarmak karmaşık bir iştir. WORKBOOK'u PNG'e aktarın format geçişleri Swift SDK'mız tarafından gerçekleştirilir ve kaynak WORKBOOK e-tablosunun ana yapısal ve mantıksal içeriği korunur. Swift kitaplığımız, ÇALIŞMA KİTABI nesnelerini çevrimiçi olarak PNG formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK, Swift geliştiricilerine güçlü işlevsellik ve mükemmel PNG çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="ÇALIŞMA KİTABI\'nı e-tablodan PNG biçimine aktarmak için REST API\'i kullanan Swift\'deki kod örneği" gistPath="" %}}
  
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
    let objectType:String = "workbook"
    let format:String = "png"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="ÇALIŞMA KİTABI\'nı PNG\'e aktarmak için Swift API nasıl kullanılır?" >}}
<li> Şu adreste bir hesap oluşturun:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
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
