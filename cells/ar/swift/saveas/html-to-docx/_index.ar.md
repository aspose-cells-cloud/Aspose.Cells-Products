---
title:  احفظ HTML كـ DOCX API لـ Swift
description:  استخدام Aspose.Cells Cloud SDK لـ Swift لحفظ ملف بتنسيق HTML كملف بتنسيق DOCX.
url: /ar/swift/saveas/html-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="سويفت API لحفظ HTML بتنسيق DOCX" h2="مكتبة سريعة لحفظ HTML كـ DOCX" p="استخدم Cells SaveAs REST API لتكوين مسارات عمل جدول بيانات مهيأة في Swift. هذا حل احترافي لحفظ HTML بتنسيق DOCX وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Swift." urlsection="saveas/html-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف HTML بتنسيق DOCX في Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من HTML كـ DOCX مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق HTML إلى DOCX بواسطة Swift SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات HTML المصدر. تعد مكتبة Swift الخاصة بنا حلاً احترافيًا لحفظ HTML كملفات DOCX عبر الإنترنت. يمنح Cloud SDK مطوري Swift وظائف قوية وإخراج DOCX مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Swift باستخدام REST API لحفظ HTML بتنسيق DOCX" gistPath="" %}}
  
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
    let name:String = BOOK1.html
    let saveOptions:PdfSaveOptions? = PdfSaveOptions(enableHTTPCompression: nil, saveFormat: "pdf", clearData: nil, cachedFileFolder: nil, validateMergedAreas: nil, refreshChartCache: nil, createDirectory: nil, sortNames: nil, calculateFormula: nil, checkFontCompatibility: nil, onePagePerSheet: true, compliance: nil, defaultFont: nil, printingPageType: nil, imageType: nil, desiredPPI: nil, jpegQuality: nil, securityOptions: nil)
    let newfilename:String = "newbook.docx"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Swift API لحفظ HTML بتنسيق DOCX" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة cellSaveAsPostDocumentSaveAs للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>macOS Monterey 12.4.0 تحديث</li>
<li>سويفت 4.2</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
