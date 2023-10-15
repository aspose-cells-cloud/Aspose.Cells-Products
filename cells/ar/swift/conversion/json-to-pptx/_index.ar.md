---
title:  تحويل JSON إلى PPTX API لـ Swift
description: استخدام Aspose.Cells Cloud SDK لـ Swift لتحويل ملف تنسيق JSON إلى ملف تنسيق PPTX.
url: /ar/swift/conversion/json-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="سويفت API لتحويل JSON إلى PPTX" h2="مكتبة سويفت لتحويل JSON إلى PPTX" p="استخدم Cells تحويل REST API لإنشاء سير عمل جدول بيانات مخصص في Swift. يعد هذا حلاً احترافيًا لتحويل JSON إلى PPTX وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Swift." urlsection="conversion/json-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل ملف JSON إلى PPTX في Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من JSON إلى PPTX مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق JSON إلى PPTX بواسطة Swift SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات JSON المصدر. تعد مكتبة Swift الخاصة بنا حلاً احترافيًا لتحويل ملفات JSON إلى ملفات PPTX عبر الإنترنت. يوفر Cloud SDK لمطوري Swift وظائف قوية ومخرجات PPTX مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على التعليمات البرمجية في Swift باستخدام REST API لتحويل JSON إلى تنسيق PPTX" gistPath="" %}}
 
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
    let workbook:String = "Book1.json"
    let format:String? = "pptx"     
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
            let fileName = "dest.pptx"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Swift API لتحويل JSON إلى PPTX" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>قم باستدعاء أسلوب cellWorkbookPutConvertWorkbook للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>ماك مونتيري 12.4</li>
<li>سويفت 4.2</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
