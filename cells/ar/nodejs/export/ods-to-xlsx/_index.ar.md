---
title: تصدير Ods إلى ملف XLSX via NodeJS
description: Aspose.Cells Cloud REST API يدعم تصدير Excel ملف وكائنات داخلية إلى أنواع ملفات التنسيق. يدعم SDK أنواع لغات التطوير. وهي تشمل Android وC# وGo وJava وNodeJS وPerl وPHP وPython وRuby وswift.
url: /ar/nodejs/export/ods-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تصدير المواد المستنفدة للأوزون إلى ملف XLSX في السحابة" h2="Excel وتصدير جداول بيانات OpenOffice باستخدام Cloud SDK مفتوح المصدر لـ NodeJS" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=" تحويل ODS إلى ملف XLSX في Cloud SDK لـ NodeJS" %}}
1.  قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا
1. تهيئة ```CellsApi``` بمعرف العميل وسر العميل وعنوان URL الأساسي وإصدار API
1. اتصل بطريقة ```cellsWorkbookPutConvertWorkbook``` للحصول على تدفق XLSX الناتج
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ابدأ مع Excel ريست API" %}}
 احصل على Excel Cloud SDK for .NET كود المصدر من[جيثب](https://github.com/aspose-cells-cloud/aspose-cells-cloud-node) لتجميع SDK بنفسك أو التوجه إلى ملف[إطلاق](https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/releases) للحصول على خيارات التنزيل البديلة.

 قم أيضًا بإلقاء نظرة على المستندة إلى Swagger[API مرجع]() لمعرفة المزيد عن[Excel الراحة API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="رمز NodeJS لتحويل المواد المستنفدة للأوزون إلى XLSX" gistPath="" %}}
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
      file: fs.createReadStream(localPath + "datasource.xlsx"),
      format: "xlsx",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
      .then((result) => {
        console.log(result)
    });

```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
