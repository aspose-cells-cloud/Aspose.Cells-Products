﻿---
title:  Swift için XLTX'i MD API olarak kaydedin
description:  XLTX formatındaki dosyayı MD formatındaki dosya olarak kaydetmek için Swift için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/swift/saveas/xltx-to-md/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLTX\'i MD olarak kaydetmek için Swift API" h2="XLTX\'i MD olarak kaydetmek için Swift kütüphanesi" p="Swift\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, Swift kullanarak XLTX\'i MD ve diğer belge formatlarında çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xltx-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="XLTX dosyasını Swift\'de MD olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını XLTX'ten MD olarak kaydetmek karmaşık bir iştir. XLTX'ten MD formatına tüm geçişler, kaynak XLTX elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken Swift SDK'mız tarafından gerçekleştirilir. Swift kitaplığımız, XLTX'i çevrimiçi olarak MD dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Swift geliştiricilerine güçlü işlevsellik ve mükemmel MD çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="XLTX\'i MD formatı olarak kaydetmek için REST API\'i kullanan Swift\'deki kod örneği" gistPath="" %}}
  
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
            return
        }
        expectation1.fulfill()
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)     
    let expectation = self.expectation(description: "saveAs")
    let name:String = BOOK1.xltx
    let saveOptions:PdfSaveOptions? = PdfSaveOptions(enableHTTPCompression: nil, saveFormat: "pdf", clearData: nil, cachedFileFolder: nil, validateMergedAreas: nil, refreshChartCache: nil, createDirectory: nil, sortNames: nil, calculateFormula: nil, checkFontCompatibility: nil, onePagePerSheet: true, compliance: nil, defaultFont: nil, printingPageType: nil, imageType: nil, desiredPPI: nil, jpegQuality: nil, securityOptions: nil)
    let newfilename:String = "newbook.md"
    let isAutoFitRows:Bool? = true
    let isAutoFitColumns:Bool? = true
    let folder:String = TEMPFOLDER
    let storageName:String? = nil        
    CellsAPI.cellsSaveAsPostDocumentSaveAs(name: name, saveOptions: saveOptions, newfilename: newfilename, isAutoFitRows: isAutoFitRows, isAutoFitColumns: isAutoFitColumns, folder: folder, storageName: storageName)
    {
        (response, error) in
        guard error == nil else {
            return
        }            
        if let response = response {
            expectation.fulfill()
        }
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="XLTX\'i MD olarak kaydetmek için Swift API nasıl kullanılır?" >}}
<li> Şu adreste bir hesap oluşturun:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için CellSaveAsPostDocumentSaveAs yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>macOS Monterey 12.4</li>
<li>Hızlı 4.2</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
