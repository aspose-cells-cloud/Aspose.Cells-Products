﻿---
title: 使用 Swift API 将 WORKSHEET 从电子表格导出为 DOCX
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
url: /zh/swift/export/worksheet-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API 将 WORKSHEET 导出为 DOCX 文件" h2="将 WORKSHEET 导出为 DOCX 文件的 Swift 库" p="使用 Cells Export REST API 以 Swift 格式导出电子表格内部对象工作流。这是一个专业的解决方案，可使用 Swift 在线将电子表格中的 WORKSHEET 导出为 DOCX 格式文件。" urlsection="export/worksheet-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Swift 中将 WORKSHEET 对象导出为 DOCX 格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 WORKSHEET 对象从电子表格导出到 DOCX 文件是一项复杂的任务。将 WORKSHEET 导出到 DOCX 格式的转换由我们的 Swift SDK 执行，同时保留源 WORKSHEET 电子表格的主要结构和逻辑内容。我们的 Swift 库是一个专业的解决方案，可在线将 WORKSHEET 对象导出到 DOCX 格式文件。此 Cloud SDK 为 Swift 开发人员提供了强大的功能和完美的 DOCX 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Swift 中的代码示例，使用 REST API 将电子表格中的 WORKSHEET 导出为 DOCX 格式" gistPath="" %}}
  
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
    let objectType:String = "worksheet"
    let format:String = "docx"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Swift API 将 WORKSHEET 导出到 DOCX" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 postExport 方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
