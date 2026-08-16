---
title: تحويل رسم بياني لملف جدول بيانات على محرك محلي إلى PDF.
description: "تقرأ هذه الطريقة رسمًا بيانيًا من ملف جدول بيانات من نظام الملفات المحلي، وتحوّله إلى تنسيق PDF المطلوب، وتعيد النتيجة المحوّلة. \nيجب تحديد مسار الملف المصدر والتنسيق الهدف بشكل صحيح. \nتأكد من وجود الأذونات اللازمة لقراءة الملف المصدر وكتابة الملف المحوّل إذا كان ذلك مناسبًا. \nتتم عملية التحويل بالكامل على خادم السحابة، مما يلغي الحاجة إلى أي تخزين سحابي أو تنزيلات خارجية. \nإذا لم يكن الملف المصدر موجودًا أو غير قابل للوصول، أو إذا حدث خطأ أثناء عملية التحويل، سيتم طرح استثناء مناسب. \nتعتمد الصيغ المدعومة للتحويل على المكتبات المتاحة وإمكاناتها."
kwords: aspose cells
url: /ar/net/convert-chart-to-pdf/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="تحويل ملفات Excel إلى صيغ أخرى" indexdesc="توفر Aspose.Cells Cloud دعمًا قويًا لتحويل صيغ ملفات Excel، وهي عملية معروفة بتعقيدها. تدعم Aspose.Cells Cloud أكثر من 30 صيغة ملف، بما في ذلك Excel، PDF، Markdown، JSON، XML، CSV، HTML، وغيرها." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="توفر Aspose.Cells Cloud واجهة REST API التي تدعم تحويل ملفات Excel إلى صيغ متعددة وتقدم مجموعات تطوير برمجيات (SDKs) لعدة لغات برمجة. تشمل هذه اللغات .NET، Java، Go، NodeJS، Python، وغيرها." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/chart/pdf"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="الصيغة للتحويل (CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}} -->
<!-- {{< blocks/products/cells/cells-cloud-showparameters >}} -->
{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}

```java
    package com.aspose.cloud.cells.api;
    import com.aspose.cloud.cells.api.CellsApi;
    import com.aspose.cloud.cells.request.*;
    public class ConvertSpreadsheetExample {
    public static void main(String[] args) {
        try {
            CellsApi api = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
            ConvertChartToImageRequest request = new ConvertChartToImageRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setchartIndex(0);
            api.ConvertChartToImage(request);
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
{{< blocks/products/pf/main-wrap-class >}}