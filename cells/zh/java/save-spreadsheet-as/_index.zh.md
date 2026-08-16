---
title: 将云存储中的电子表格转换为指定格式。
description: 此方法直接从云存储访问电子表格文件，将其转换为所需的输出格式（例如 XLSX、PDF、CSV），并在不将文件下载到本地系统的情况下返回转换结果。\n确保已正确设置云存储配置（如访问凭证和文件路径）。\n转换过程完全在云环境中完成，最小化数据传输开销，并通过将敏感数据保留在云基础设施内来增强安全性。\n如果源文件不存在，或在转换过程中出现错误，将抛出相应的异常。\n支持的输出格式取决于底层转换服务的能力。
kwords: aspose 单元格
url: /zh/net/save-spreadsheet-as/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="将 Excel 文件转换为其他格式" indexdesc="Aspose.Cells Cloud 提供对 Excel 文件格式转换的强大支持，这一过程以其复杂性而闻名。Aspose.Cells Cloud 支持 30 多种文件格式，包括 Excel、Pdf、Markdown、Json、XML、Csv、Html 等等。" >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="支持的特性" featuremsg="Aspose.Cells Cloud 提供支持将 Excel 文件转换为多种格式的 REST API，并为多种编程语言提供 SDK。这些编程语言包括 .NET、Java、Go、NodeJS、Python 等等。" >}}
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