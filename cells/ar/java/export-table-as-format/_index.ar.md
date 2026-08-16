---
title: تحويل جدول من جدول بيانات في التخزين السحابي إلى الصيغة المحددة.
description: تعالج هذه الطريقة جدولاً من جدول بيانات مباشرةً في التخزين السحابي، وتحوله إلى صيغة الإخراج المطلوبة (PDF أو صيغة صورة) دون الحاجة إلى تنزيل الملف إلى الجهاز المحلي.\nتعتمد العملية على بيانات اعتماد التخزين السحابي الصالحة ومسار ملف أو معرف يمكن الوصول إليه.\nيتم إجراء التحويل عن بُعد، مما يقلل من نقل البيانات ويحسن الأداء للملفات الكبيرة.\nإذا لم يتم العثور على ملف المصدر، أو تم رفض الوصول، أو حدث خطأ أثناء التحويل، سيتم إلقاء استثناء مناسب.\nيتم تحديد صيغ الإخراج المدعومة بناءً على قدرات خدمة التحويل السحابي الأساسية.
kwords: aspose خلايا
url: /ar/java/export-table-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="تحويل ملفات إكسل إلى صيغ أخرى" indexdesc="Aspose.Cells Cloud يوفر دعماً قوياً لتحويل صيغ ملفات إكسل، وهي عملية تعرف بتعقيدها. Aspose.Cells Cloud يدعم أكثر من 30 صيغة ملف، بما في ذلك Excel، Pdf، Markdown، Json، XML، Csv، Html، وغيرها." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="الميزات المدعومة" featuremsg="Aspose.Cells Cloud يقدم واجهة برمجة تطبيقات REST تدعم تحويل ملفات إكسل إلى صيغ مختلفة وتوفر مجموعات تطوير (SDKs) للعديد من لغات البرمجة. تشمل هذه اللغات .Net، Java، Go، NodeJS، Python، وغيرها." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="/cells/{name}/worksheets/{worksheet}/tables/{tableName}"  %}}

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
            ExportTableAsFormatRequest request = new ExportTableAsFormatRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.ExportTableAsFormat(request);
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