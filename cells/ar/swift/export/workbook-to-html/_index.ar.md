---
title:  قم بتصدير كتاب العمل إلى HTML من جدول البيانات باستخدام Swift API
description:  Aspose.Cells Cloud REST API يدعم تصدير {0} إلى {1} تنسيق الملفات باستخدام {2}.
url: /ar/swift/export/workbook-to-html/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="سويفت API لتصدير كتاب العمل إلى ملف HTML" h2="مكتبة سويفت لتصدير كتاب العمل إلى ملف HTML" p="استخدم Cells Export REST API لتصدير مسارات عمل العناصر الداخلية لجدول البيانات في Swift. هذا حل احترافي لتصدير كتاب العمل إلى ملف بتنسيق HTML من جدول بيانات عبر الإنترنت باستخدام Swift." urlsection="export/workbook-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن WORKBOOK إلى ملف بتنسيق HTML في Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن WORKBOOK إلى ملف HTML من جدول البيانات مهمة معقدة. تصدير كتاب العمل إلى HTML يتم تنفيذ انتقالات تنسيق بواسطة Swift SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات WORKBOOK المصدر. تعد مكتبة Swift الخاصة بنا حلاً احترافيًا لتصدير كائنات WORKBOOK إلى ملفات بتنسيق HTML عبر الإنترنت. يمنح Cloud SDK مطوري Swift وظائف قوية وإخراج HTML مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال التعليمات البرمجية في Swift باستخدام REST API لتصدير كتاب العمل إلى تنسيق HTML من جدول البيانات" gistPath="" %}}
  
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
    let format:String = "html"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Swift API لتصدير WORKBOOK إلى HTML" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
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
