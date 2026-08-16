---
title: 将 Excel 文件转换为其他格式。
description: Aspose.Cells Cloud 提供对 Excel 文件格式转换的强大支持，这一过程以其复杂性而著称。Aspose.Cells Cloud 支持 30 多种文件格式，包括 Excel、Pdf、Markdown、Json、XML、Csv、Html 等。
kwords: aspose cells
url: /zh/java/export-worksheet-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud 功能" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="将 Excel 文件转换为其他格式" indexdesc="Aspose.Cells Cloud 提供对 Excel 文件格式转换的强大支持，这一过程以其复杂性而著称。Aspose.Cells Cloud 支持 30 多种文件格式，包括 Excel、Pdf、Markdown、Json、XML、Csv、Html 等。" >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="支持的功能" featuremsg="Aspose.Cells Cloud 提供支持将 Excel 文件转换为多种格式的 REST API，并为多种编程语言提供 SDK。这些编程语言包括 .Net、Java、Go、NodeJS、Python 等。" >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="https://api.aspose.cloud/v4.0/cells/{name}/worksheets/{worksheet}"  %}}

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
            ExportWorksheetAsFormatRequest request = new ExportWorksheetAsFormatRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setformat("pdf");
            api.ExportWorksheetAsFormat(request);
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