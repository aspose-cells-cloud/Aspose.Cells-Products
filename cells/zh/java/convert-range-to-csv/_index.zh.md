---
title: 将本地驱动器上的电子表格范围转换为 CSV 文件。
description: 此方法从本地文件系统读取电子表格文件，将其指定范围转换为所需的 CSV 文件，并返回转换结果。必须正确指定源文件路径和目标格式。确保具备读取源文件和（如适用）写入转换后文件的必要权限。转换过程完全在云服务器上执行，无需任何云存储或外部下载。如果源文件不存在、不可访问，或在转换过程中出现错误，将抛出相应的异常。支持的转换格式取决于可用库及其功能。
kwords: Aspose Cells
url: /zh/net/convert-range-to-csv/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells 云功能" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="将 Excel 文件转换为其他格式" indexdesc="Aspose.Cells Cloud 为 Excel 文件格式转换提供强大的支持，这一过程以其复杂性著称。Aspose.Cells Cloud 支持 30 多种文件格式，包括 Excel、Pdf、Markdown、Json、XML、Csv、Html 等。" >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="支持的功能" featuremsg="Aspose.Cells Cloud 提供支持将 Excel 文件转换为多种格式的 REST API，并为多种编程语言提供 SDK。这些编程语言包括 .NET、Java、Go、NodeJS、Python 等。" >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/range/csv"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers).">}} -->
<!-- {{< blocks/products/cells/cells-cloud-showparameters >}} -->
{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}


```java
    package com.aspose.cloud.cells.api;
    import com.aspose.cloud.cells.api.CellsApi;
    import com.aspose.cloud.cells.request.*;
    public class ConvertSpreadsheetExample {
    public static void main(String[] args) {
        try {
            CellsApi api = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
            ConvertRangeToCsvRequest request = new ConvertRangeToCsvRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setcloud("A1:C10");
            api.ConvertRangeToCsv(request);
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