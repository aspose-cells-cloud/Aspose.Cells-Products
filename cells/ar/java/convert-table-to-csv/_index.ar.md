---
title: تحويل جدول من جدول بيانات على القرص المحلي إلى ملف CSV.
description: تقوم هذه الطريقة بقراءة ملف جدول بيانات من نظام الملفات المحلي، وتحويل جدولّه إلى ملف CSV المطلوب، وإرجاع النتيجة المحوّلة. \nيجب تحديد مسار ملف المصدر وتنسيق الهدف بشكل صحيح. \nتأكد من وجود الأذونات اللازمة لقراءة ملف المصدر وكتابة الملف المحوّل إذا كان ذلك مطلوباً. \nتتم عملية التحويل بالكامل على خادم السحابة، مما يلغي الحاجة إلى أي تخزين سحابي أو تحميلات خارجية. \nإذا لم يكن ملف المصدر موجودًا أو كان غير قابل للوصول، أو إذا حدث خطأ أثناء عملية التحويل، سيتم طرح استثناء مناسب. \nتعتمد الصيغ المدعومة للتحويل على المكتبات المتاحة وقدراتها.
kwords: aspose cells
url: /ar/java/convert-table-to-csv/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convert Excel files to other formats" indexdesc="Aspose.Cells Cloud provides robust support for Excel file format conversion, a process known for its intricacy. Aspose.Cells Cloud supports 30+ file formats, including Excel, Pdf, Markdown, Json, XML, Csv, Html, and so on.">}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="Aspose.Cells Cloud provides REST API which supports converting Excel files to various format and offers SDKs for multiple programming languages. These programming languages are include of Net, Java, Go, NodeJS, Python, and so on. .">}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/table/csv"  %}}

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
{{< blocks/products/pf/main-wrap-class >}}