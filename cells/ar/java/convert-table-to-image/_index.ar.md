---
title: تحويل جدول من جدول بيانات على محرك محلي إلى ملف صورة.
description: تقوم هذه الطريقة بقراءة ملف جدول بيانات من نظام الملفات المحلي، وتحويل جدولَه إلى ملف صورة مطلوب، وإرجاع النتيجة المحوَّلة. \nيجب تحديد مسار ملف المصدر وصيغة الهدف بشكل صحيح. \nتأكد من وجود الأذونات اللازمة لقراءة ملف المصدر وكتابة الملف المحوَّل إذا كان ذلك مناسبًا. \nتحدث عملية التحويل بالكامل على خادم السحابة، مما يلغي الحاجة إلى أي تخزين سحابي أو تنزيلات خارجية. \nإذا كان ملف المصدر غير موجود أو غير قابل للوصول، أو إذا حدث خطأ أثناء عملية التحويل، سيتم رمي استثناء مناسب. \nتعتمد الصيغ المدعومة للتحويل على المكتبات المتاحة وقدراتها.
kwords: aspose cells
url: /ar/net/convert-table-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="تحويل ملفات Excel إلى صيغ أخرى" indexdesc="توفر Aspose.Cells Cloud دعمًا قويًا لتحويل صيغ ملفات Excel، وهو عملية معروفة بتعقيدها. تدعم Aspose.Cells Cloud أكثر من 30 صيغة ملف، بما في ذلك Excel، PDF، Markdown، JSON، XML، CSV، HTML، وغيرها." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="الميزات المدعومة" featuremsg="توفر Aspose.Cells Cloud واجهة برمجة تطبيقات REST التي تدعم تحويل ملفات Excel إلى صيغ مختلفة وتقدم SDKs للعديد من لغات البرمجة. تشمل هذه اللغات .NET، Java، Go، NodeJS، Python، وغيرها." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/table/image"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers).">}} -->
<!-- {{< blocks/products/cells/cells-cloud-showparameters >}} -->
{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}

```java
    package com.aspose.cloud.cells.api;
    import com.aspose.cloud.cells.api.CellsApi;
    import com.aspose.cloud.cells.request.*;
    public class Example {
    public static void main(String[] args) {
        try {
            CellsApi api = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
            ConvertWorksheetToImageRequest request = new ConvertWorksheetToImageRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.settableName("table1");
            request.setformat("png");
            api.ConvertWorksheetToImage(request);
        } catch (ApiException e) {
            e.printStackTrace();
        }
    }
}
```

{{% /blocks/products/cells/cells-cloud-showcode %}}
<!-- {{< /blocks/products/cells/cells-cloud-run-conversion >}} -->



{{< blocks/products/cells/cells-cloud-available-sdks >}}





{{< /blocks/products/pf/main-container >}}


{{< blocks/products/cells/cells-cloud-resource-links >}}
{{< /blocks/products/pf/main-wrap-class >}}