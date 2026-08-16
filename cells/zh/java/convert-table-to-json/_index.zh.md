---
title: 将本地驱动器上的电子表格表格转换为 json 文件。
description: 此方法从本地文件系统读取电子表格文件，将其表格转换为所需的 html 文件，并返回转换结果。 \n必须正确指定源文件路径和目标格式。 \n确保具备读取源文件和（如适用）写入转换后文件的必要权限。 \n转换过程完全在云服务器上进行，消除对任何云存储或外部下载的需求。 \n如果源文件不存在、无法访问，或在转换过程中出现错误，将抛出相应的异常。 \n支持的转换格式取决于可用库及其功能。
kwords: aspose cells
url: /zh/net/convert-table-to-json/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells 云功能" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="将 Excel 文件转换为其他格式" indexdesc="Aspose.Cells Cloud 提供对 Excel 文件格式转换的强大支持，这一过程因其复杂性而闻名。Aspose.Cells Cloud 支持 30+ 文件格式，包括 Excel、Pdf、Markdown、Json、XML、Csv、Html 等。" >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="支持的功能" featuremsg="Aspose.Cells Cloud 提供 REST API，支持将 Excel 文件转换为各种格式，并为多种编程语言提供 SDK。这些编程语言包括 .Net、Java、Go、NodeJS、Python 等。" >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/table/json"  %}}

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
            ConvertTableToJsonRequest request = new ConvertTableToJsonRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.settableName("table1");
            api.ConvertTableToJson(request);
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