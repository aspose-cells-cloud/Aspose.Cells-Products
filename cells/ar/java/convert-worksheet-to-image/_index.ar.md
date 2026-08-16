---
title: تحويل ورقة عمل من جدول بيانات على قرص محلي إلى تنسيق صورة.
description: هذه الطريقة تقرأ ملف جدول بيانات من نظام الملفات المحلي، تحويل ورقة العمل إلى تنسيق الصورة المطلوب (مثل svg، png، ...) وتعيد النتيجة المحولة.\nيجب تحديد مسار الملف المصدر والتنسيق الهدف بشكل صحيح.\nتأكد من أن الأذونات اللازمة موجودة لقراءة الملف المصدر وكتابة الملف المحول إذا كان ذلك مناسبًا.\nعملية التحويل تتم بالكامل على خادم السحابة، مما يلغي الحاجة إلى أي تخزين سحابي أو تنزيلات خارجية.\nإذا لم يكن الملف المصدر موجودًا أو غير قابل للوصول، أو إذا حدث خطأ أثناء عملية التحويل، سيتم إطلاق استثناء مناسب.\nالصيغ المدعومة للتحويل تعتمد على المكتبات المتاحة وقدراتها.
kwords: aspose cells
url: /ar/net/convert-worksheet-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="ميزة سحابة الخلايا" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="تحويل ملفات Excel إلى تنسيقات أخرى" indexdesc="توفر Aspose.Cells Cloud دعمًا قويًا لتحويل صيغ ملفات Excel، وهي عملية معروفة بتعقيدها. تدعم Aspose.Cells Cloud أكثر من 30 صيغة ملف، بما في ذلك Excel، Pdf، Markdown، Json، XML، Csv، Html، وغيرها." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="الميزات المدعومة" featuremsg="توفر Aspose.Cells Cloud واجهة برمجة تطبيقات REST التي تدعم تحويل ملفات Excel إلى صيغ مختلفة وتوفر SDKs لعدة لغات برمجة. تشمل هذه اللغات .Net، Java، Go، NodeJS، Python، وغيرها." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/worksheet/image"  %}}

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