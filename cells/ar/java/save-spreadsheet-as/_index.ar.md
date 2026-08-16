---
title: تحويل جدول بيانات في التخزين السحابي إلى الصيغة المحددة.
description: تقوم هذه الطريقة بالوصول إلى ملف جدول بيانات مباشرةً من التخزين السحابي، وتحويله إلى صيغة الإخراج المطلوبة (مثل XLSX، PDF، CSV)، وإرجاع النتيجة المحوّلة دون تنزيل الملف إلى النظام المحلي. \nتأكد من إعداد تكوين التخزين السحابي (مثل بيانات الاعتماد ومسار الملف) بشكل صحيح. \nتتم عملية التحويل بالكامل داخل بيئة السحابة، مما يقلل من عبء نقل البيانات ويعزز الأمان من خلال إبقاء البيانات الحساسة داخل بنية السحابة التحتية. \nإذا كان ملف المصدر غير موجود، أو إذا حدث خطأ أثناء عملية التحويل، سيتم رفع استثناء مناسب. \nتعتمد صيغ الإخراج المدعومة على قدرات خدمة التحويل الأساسية.
kwords: aspose cells
url: /ar/net/save-spreadsheet-as/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="تحويل ملفات إكسل إلى صيغ أخرى" indexdesc="توفر Aspose.Cells Cloud دعماً قوياً لتحويل صيغ ملفات إكسل، وهي عملية معروفة بتعقيدها. تدعم Aspose.Cells Cloud أكثر من 30 صيغة ملف، بما في ذلك Excel، Pdf، Markdown، Json، XML، Csv، Html، وغيرها." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="الميزات المدعومة" featuremsg="توفر Aspose.Cells Cloud واجهة برمجة تطبيقات REST تدعم تحويل ملفات إكسل إلى صيغ مختلفة وتقدم مجموعات تطوير برمجيات (SDKs) للعديد من لغات البرمجة. تشمل هذه اللغات .NET, Java, Go, NodeJS, Python، وغيرها." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/{name}/saveas"  %}}

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
            SaveSpreadsheetAsRequest request = new SaveSpreadsheetAsRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.SaveSpreadsheetAs(request);
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