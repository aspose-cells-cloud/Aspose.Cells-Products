---
title: تحويل مخطط من جدول بيانات على محرك أقراص محلي إلى صورة.
description: "تقرأ هذه الطريقة مخططاً من ملف جدول بيانات من نظام الملفات المحلي، وتحوله إلى تنسيق الصورة المطلوب (مثل PNG، SVG، Tiff)، وتعيد النتيجة المحوّلة. \nيجب تحديد مسار ملف المصدر وتنسيق الهدف بشكل صحيح. \nتأكد من وجود الأذونات اللازمة لقراءة ملف المصدر وكتابة الملف المحوّل إذا كان ذلك مناسباً. \nتتم عملية التحويل بالكامل على خادم السحابة، مما يلغي الحاجة إلى أي تخزين سحابي أو تنزيلات خارجية. \nإذا كان ملف المصدر غير موجود، أو غير قابل للوصول، أو حدث خطأ أثناء عملية التحويل، سيتم إلقاء استثناء مناسب. \nتعتمد الصيانات المدعومة للتحويل على المكتبات المتاحة وقدراتها."
kwords: aspose cells
url: /ar/java/convert-chart-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="ميزة سحابة Cells" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="تحويل ملفات Excel إلى صيغ أخرى" indexdesc="توفر Aspose.Cells Cloud دعماً قوياً لتحويل صيغ ملفات Excel، وهي عملية معروفة بتعقيدها. تدعم Aspose.Cells Cloud أكثر من 30 صيغة ملف، بما في ذلك Excel وPdf وMarkdown وJson وXML وCsv وHtml وغيرها." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="الميزات المدعومة" featuremsg="توفر Aspose.Cells Cloud واجهة REST API التي تدعم تحويل ملفات Excel إلى صيغ مختلفة وتقدم SDKs للعديد من لغات البرمجة. تشمل هذه اللغات .Net وJava وGo وNodeJS وPython وغيرها." .>}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/chart/image"  %}}

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
            request.setformat("png");
            api.ConvertChartToImage(request);
        } catch (ApiException e) {
            e.printStackTrace();
        }
    }
}
```

{{% /blocks/products/cells/cells-cloud-showcode %}}



{{< blocks/products/cells/cells-cloud-available-sdks >}}





{{< /blocks/products/pf/main-container >}}


{{< blocks/products/cells/cells-cloud-resource-links >}}
{{< /blocks/products/pf/main-wrap-class >}}