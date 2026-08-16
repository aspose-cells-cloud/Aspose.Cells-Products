---
title: 将云存储中的电子表格范围转换为指定格式。
description: 此方法直接在云存储中处理电子表格范围，将其转换为请求的输出格式（PDF 或图像格式），无需将文件下载到本地机器。\n该操作依赖有效的云存储凭证以及可访问的文件路径或标识符。\n转换在远程执行，减少数据传输并提升大文件的性能。\n如果未找到源文件、访问被拒绝或转换过程中出现错误，将抛出相应的异常。\n支持的输出格式由底层云转换服务的能力决定。
kwords: aspose cells
url: /zh/java/export-range-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="将 Excel 文件转换为其他格式" indexdesc="Aspose.Cells Cloud 提供强大的 Excel 文件格式转换支持，这一过程以其复杂性著称。Aspose.Cells Cloud 支持 30 多种文件格式，包括 Excel、Pdf、Markdown、Json、XML、Csv、Html 等。" >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="支持的功能" featuremsg="Aspose.Cells Cloud 提供支持将 Excel 文件转换为各种格式的 REST API，并为多种编程语言提供 SDK。这些编程语言包括 .NET、Java、Go、NodeJS、Python 等。" >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="/cells/{name}/worksheets/{worksheet}/ranges/{range}"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="要转换的格式 (CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)。">}} -->
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
            ExportRangeAsFormatRequest request = new ExportRangeAsFormatRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.ExportRangeAsFormat(request);
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