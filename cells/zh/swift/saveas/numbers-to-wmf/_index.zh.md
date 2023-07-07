---
title: 将 Swift 的数字另存为 WMF API
description: 使用 Aspose.Cells Cloud SDK for Swift 将 NUMBERS 格式文件保存为 WMF 格式文件。
url: /zh/swift/saveas/numbers-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API 将数字保存为 WMF" h2="将 NUMBERS 保存为 WMF 的 Swift 库" p="使用 Cells SaveAs REST API 在 Swift 中创建自定义电子表格工作流程。这是一个使用 Swift 在线将 NUMBERS 保存为 WMF 和其他文档格式的专业解决方案。" urlsection="saveas/numbers-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Swift 中将 NUMBERS 文件另存为 WMF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 NUMBERS 文件格式保存为 WMF 是一项复杂的任务。所有 NUMBERS 到 WMF 格式的转换均由我们的 Swift SDK 执行，同时保留源 NUMBERS 电子表格的主要结构和逻辑内容。我们的 Swift 库是在线将 NUMBERS 保存为 WMF 文件的专业解决方案。此 Cloud SDK 为 Swift 开发人员提供了强大的功能和完美的 WMF 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Swift 中使用 REST API 将 NUMBERS 保存为 WMF 格式的代码示例" gistPath="" %}}
  
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
    let name:String = BOOK1.numbers
    let saveOptions:PdfSaveOptions? = PdfSaveOptions(enableHTTPCompression: nil, saveFormat: "pdf", clearData: nil, cachedFileFolder: nil, validateMergedAreas: nil, refreshChartCache: nil, createDirectory: nil, sortNames: nil, calculateFormula: nil, checkFontCompatibility: nil, onePagePerSheet: true, compliance: nil, defaultFont: nil, printingPageType: nil, imageType: nil, desiredPPI: nil, jpegQuality: nil, securityOptions: nil)
    let newfilename:String = "newbook.wmf"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Swift API 将 NUMBERS 保存为 WMF" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsSaveAsPostDocumentSaveAs 方法来获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>macOS 蒙特利 12.4</li>
<li>斯威夫特 4.2</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
