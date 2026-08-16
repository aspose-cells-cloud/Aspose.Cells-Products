---
title: تحويل مخطط من جدول بيانات في التخزين السحابي إلى التنسيق المحدد.
description: تعالج هذه الطريقة مخطط جدول البيانات مباشرة في التخزين السحابي، وتحوله إلى تنسيق الإخراج المطلوب (PDF أو تنسيق صورة) دون الحاجة إلى تنزيل الملف إلى الجهاز المحلي. \nتعتمد العملية على بيانات اعتماد تخزين سحابي صالحة ومسار ملف أو معرف يمكن الوصول إليه. \nيتم تنفيذ التحويل عن بُعد، مما يقلل من نقل البيانات ويُحسِّن الأداء للملفات الكبيرة. \nإذا لم يتم العثور على الملف المصدر، أو تم رفض الوصول، أو وقع خطأ أثناء التحويل، فسيتم إلقاء استثناء مناسب. \nتنسيقات الإخراج المدعومة تُحدد بناءً على قدرات خدمة التحويل السحابي الأساسية.
kwords: aspose cells
url: /ar/java/export-chart-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="تحويل ملفات Excel إلى صيغ أخرى" indexdesc="توفر Aspose.Cells Cloud دعماً قوياً لتحويل صيغ ملفات Excel، وهي عملية معروفة بتعقيدها. تدعم Aspose.Cells Cloud أكثر من 30 صيغة ملف، بما في ذلك Excel, Pdf, Markdown, Json, XML, Csv, Html، وغيرها." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="ميزات مدعومة" featuremsg="توفر Aspose.Cells Cloud واجهة برمجة تطبيقات REST تدعم تحويل ملفات Excel إلى صيغ متعددة وتقدم حزم تطوير برمجيات (SDKs) للعديد من لغات البرمجة. تشمل هذه اللغات .Net, Java, Go, NodeJS, Python، وغيرها." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="https://api.aspose.cloud/v4.0/cells/{name}/worksheets/{worksheet}/charts/{chartIndex}"  %}}

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
            ExportChartAsFormatRequest request = new ExportChartAsFormatRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.ExportChartAsFormat(request);
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