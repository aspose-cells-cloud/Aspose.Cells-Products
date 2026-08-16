---
title: تحويل جدول من جدول بيانات على محرك أقراص محلي إلى ملف html.
description: هذه الطريقة تقرأ ملف جدول بيانات من نظام الملفات المحلي، وتحويل جدولها إلى ملف html المطلوب، وتعيد النتيجة المحولة. \nيجب تحديد مسار ملف المصدر وصيغة الهدف بشكل صحيح. \nتأكد من وجود الأذونات اللازمة لقراءة الملف المصدر وكتابة الملف المحول إذا كان ذلك مناسبًا. \nتتم عملية التحويل بالكامل على خادم السحابة، مما يلغي الحاجة إلى أي تخزين سحابي أو تنزيلات خارجية. \nإذا لم يكن ملف المصدر موجودًا، أو غير قابل للوصول، أو حدث خطأ أثناء عملية التحويل، سيتم طرح استثناء مناسب. \nالصيغ المدعومة للتحويل تعتمد على المكتبات المتاحة وقدراتها.
kwords: aspose cells
url: /ar/net/convert-table-to-html/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="ميزة سحابة Cells" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="تحويل ملفات Excel إلى صيغ أخرى" indexdesc="Aspose.Cells Cloud يوفر دعمًا قويًا لتحويل صيغ ملفات Excel، وهي عملية معروفة بتعقيدها. يدعم Aspose.Cells Cloud أكثر من 30 صيغة ملف، بما في ذلك Excel، Pdf، Markdown، Json، XML، Csv، Html، وغيرها." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="الميزات المدعومة" featuremsg="Aspose.Cells Cloud يوفر واجهة REST API التي تدعم تحويل ملفات Excel إلى صيغ متعددة وتقدم مجموعات تطوير SDK لعدة لغات برمجة. تشمل هذه اللغات .Net، Java، Go، NodeJS، Python، وغيرها." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/table/html"  %}}

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
            ConvertTableToHtmlRequest request = new ConvertTableToHtmlRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.settableName("table1");
            api.ConvertTableToHtml(request);
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