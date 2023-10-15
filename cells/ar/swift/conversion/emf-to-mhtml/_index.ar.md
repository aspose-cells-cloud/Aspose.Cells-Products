---
title:  EMF إلى MHTML تحويل API إلى Swift
description: استخدام Aspose.Cells Cloud SDK لـ Swift لتحويل ملف تنسيق EMF إلى ملف تنسيق MHTML.
url: /ar/swift/conversion/emf-to-mhtml/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="سويفت API لتحويل EMF إلى MHTML" h2="مكتبة سويفت لتحويل EMF إلى MHTML" p="استخدم Cells تحويل REST API لإنشاء سير عمل جدول بيانات مخصص في Swift. يعد هذا حلاً احترافيًا لتحويل EMF إلى MHTML وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Swift." urlsection="conversion/emf-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل ملف EMF إلى MHTML في Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من EMF إلى MHTML مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق EMF إلى MHTML بواسطة Swift SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات EMF. تعد مكتبة Swift الخاصة بنا حلاً احترافيًا لتحويل EMF إلى ملفات MHTML عبر الإنترنت. يوفر Cloud SDK لمطوري Swift وظائف قوية ومخرجات MHTML مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على التعليمات البرمجية في Swift باستخدام REST API لتحويل EMF إلى تنسيق MHTML" gistPath="" %}}
 
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
    let workbook:String = "Book1.emf"
    let format:String? = "mhtml"     
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
            let fileName = "dest.mhtml"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Swift API لتحويل EMF إلى MHTML" >}}
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
