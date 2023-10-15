---
title: تصدير Ods إلى ملف XLSX via Swift
description: Aspose.Cells Cloud REST API يدعم تصدير Excel ملف وكائنات داخلية إلى أنواع ملفات التنسيق. يدعم SDK أنواع لغات التطوير. وهي تشمل Android وC# وGo وJava وNodeJS وPerl وPHP وPython وRuby وswift.
url: /ar/swift/export/ods-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تصدير المواد المستنفدة للأوزون إلى ملف XLSX في السحابة" h2="Excel وتصدير جداول بيانات OpenOffice باستخدام Cloud SDK مفتوح المصدر لـ Swift" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=" تصدير ODS إلى ملف XLSX في Cloud SDK لـ Swift" %}}
1.  قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا
1. تهيئة ```CellsApi``` بمعرف العميل وسر العميل وعنوان URL الأساسي وإصدار API
1. اتصل بطريقة ```cellsWorkbookPutConvertWorkbook``` للحصول على تدفق XLSX الناتج
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ابدأ مع Excel ريست API" %}}
 احصل على Excel Cloud SDK for .NET كود المصدر من[جيثب](https://github.com/aspose-cells-cloud/aspose-cells-cloud-swift) لتجميع SDK بنفسك أو التوجه إلى ملف[إطلاق](https://github.com/aspose-cells-cloud/aspose-cells-cloud-swift/releases) للحصول على خيارات التنزيل البديلة.

 قم أيضًا بإلقاء نظرة على المستندة إلى Swagger[API مرجع]() لمعرفة المزيد عن[Excel الراحة API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="كود سويفت لتحويل المواد المستنفدة للأوزون إلى XLSX" gistPath="" %}}
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
    let workbook:String = "Book1.xlsx"
    let format:String? = "xlsx"     
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
            let fileName = "dest.xlsx"
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

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
