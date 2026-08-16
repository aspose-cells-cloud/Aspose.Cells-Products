---
title: تحويل ملفات Excel إلى صيغ أخرى.
description: يوفر Aspose.Cells Cloud دعمًا قويًا لتحويل صيغ ملفات Excel، وهي عملية معروفة بتعقيدها. يدعم Aspose.Cells Cloud أكثر من 30 صيغة ملف، بما في ذلك Excel و Pdf و Markdown و Json و XML و Csv و Html وغيرها.
kwords: aspose cells
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="ميزة Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="تحويل ملفات Excel إلى صيغ أخرى" indexdesc="يوفر Aspose.Cells Cloud دعمًا قويًا لتحويل صيغ ملفات Excel، وهي عملية معروفة بتعقيدها. يدعم Aspose.Cells Cloud أكثر من 30 صيغة ملف، بما في ذلك Excel و Pdf و Markdown و Json و XML و Csv و Html وغيرها." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="الميزات المدعومة" featuremsg="يوفر Aspose.Cells Cloud واجهة برمجة تطبيقات REST تدعم تحويل ملفات Excel إلى صيغ مختلفة وتوفر مجموعات تطوير برامج (SDKs) للعديد من لغات البرمجة. تشمل هذه اللغات .NET و Java و Go و NodeJS و Python وغيرها." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="https://api.aspose.cloud/v4.0/cells/cells/{name}"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="تشغيل الكود" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="الصيغة المراد تحويلها (CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}} -->
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
            ExportSpreadsheetAsFormatRequest request = new ExportSpreadsheetAsFormatRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.ExportSpreadsheetAsFormat(request);
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