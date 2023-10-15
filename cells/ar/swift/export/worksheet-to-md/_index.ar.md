---
title:  تصدير ورقة عمل إلى MD من جدول البيانات باستخدام Swift API
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
url: /ar/swift/export/worksheet-to-md/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="سويفت API لتصدير ورقة العمل إلى ملف MD" h2="مكتبة سويفت لتصدير ورقة العمل إلى ملف MD" p="استخدم Cells تصدير REST API لتصدير سير عمل الكائنات الداخلية لجدول البيانات في Swift. يعد هذا حلاً احترافيًا لتصدير ورقة العمل إلى ملف بتنسيق MD من جدول البيانات عبر الإنترنت باستخدام Swift." urlsection="export/worksheet-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن ورقة العمل إلى ملف بتنسيق MD في Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن ورقة العمل إلى ملف MD من جدول البيانات مهمة معقدة. يتم تنفيذ انتقالات تصدير ورقة العمل إلى تنسيق MD بواسطة Swift SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات المصدر. تعد مكتبة Swift الخاصة بنا حلاً احترافيًا لتصدير كائنات WORKSHEET إلى ملفات بتنسيق MD عبر الإنترنت. يوفر Cloud SDK لمطوري Swift وظائف قوية ومخرجات MD مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على التعليمات البرمجية في Swift باستخدام REST API لتصدير ورقة عمل إلى تنسيق MD من جدول البيانات" gistPath="" %}}
  
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
    let format:String = "md"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Swift API لتصدير ورقة العمل إلى MD" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة postExport للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
