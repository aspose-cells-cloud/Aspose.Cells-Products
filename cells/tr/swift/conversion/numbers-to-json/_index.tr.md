---
title:  NUMBERS'den JSON'a Swift için API'i Dönüştür
description:  NUMBERS biçim dosyasını JSON biçim dosyasına dönüştürmek için Aspose.Cells Cloud SDK for Swift'i kullanma.
url: /tr/swift/conversion/numbers-to-json/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="SAYILARI JSON\'a dönüştürmek için Swift API" h2="NUMBERS\'i JSON\'a dönüştürmek için Swift kitaplığı" p="Swift\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, Swift kullanarak çevrimiçi olarak NUMBERS\'i JSON\'a ve diğer belge biçimlerine dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/numbers-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir NUMBERS dosyasını Swift\'de JSON\'a dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya biçimlerini NUMBERS'den JSON'a dönüştürmek karmaşık bir iştir. Tüm NUMBERS'tan JSON formatına geçişler, kaynak NUMBERS e-tablonun ana yapısal ve mantıksal içeriğini korurken Swift SDK'mız tarafından gerçekleştirilir. Swift kitaplığımız, NUMBERS'i çevrimiçi olarak JSON dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, Swift geliştiricilerine güçlü işlevsellik ve mükemmel JSON çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="SAYILARI JSON formatına dönüştürmek için REST API kullanan Swift kod örneği" gistPath="" %}}
 
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
    let expectation = self.expectation(description: "PutConvert")
    let workbook:String = "Book1.numbers"
    let format:String? = "json"     
    let url1: URL? = getURL(workbook)
    let filedata = NSData(contentsOfFile: url1!.path)
    let password:String? = nil
    let outPath:String? = nil
    CellsAPI.cellsWorkbookPutConvertWorkbook(file: url1!, format: format, password: password, outPath: outPath)
    {
        (response, error) in
        guard error == nil else {
            let errorinfo = self.GetErrorDataInfo(error: error as! ErrorResponse)
            print("error info: \(errorinfo!)")
            XCTFail("error PutConvert")
            return
        }            
        if let response = response {
            //response is a Data of file, we may write it down and check it.
            let fileName = "dest.json"
            let filePath = NSHomeDirectory()
            let fileManager = FileManager.default
            let path = "\(filePath)/tmp/\(fileName)"
            fileManager.createFile(atPath: path, contents:nil, attributes:nil)
            let handle = FileHandle(forWritingAtPath:path)
            handle?.write(response as Data)
            expectation.fulfill()
        }
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="SAYILARI JSON\'a dönüştürmek için Swift API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için cellsWorkbookPutConvertWorkbook yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>macOS Monterey 12.4</li>
<li>hızlı 4.2</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
