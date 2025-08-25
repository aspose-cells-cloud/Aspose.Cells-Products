---
title: Merge cells in the worksheet.
description: Aspose.Cells Cloud provides robust support for merging cells in the worksheet, a process known for its intricacy.

---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Merge cells in the worksheet" indexdesc="Aspose.Cells Cloud provides robust support for merging cells in the worksheet, a process known for its intricacy.">}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="Aspose.Cells Cloud provides REST API which supports merging cells in the worksheet and offers SDKs for multiple programming languages. These programming languages are include of Net, Java, Go, NodeJS, Python, and so on.">}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}



{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl=s://api.aspose.cloud/v4.0/cells/merge/spreadsheet  %}}


{{< blocks/products/cells/cells-cloud-run-merge btName="RunCode" OutResultType="Variable" OutResultDataType="Class" ResponseType="FileInfo" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/DataProcessing/MergeSpreadsheets" >}}
{{< blocks/products/cells/cells-cloud-upload>}}

{{< blocks/products/cells/cells-cloud-parameters itName="outFormat"  required="False" prompt="The output data file format.(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)">}}
<!-- {{< blocks/products/cells/cells-cloud-parameters itName="mergeToOneSheet"  required="False" prompt="Merge all workbooks into a sheet.">}}
{{< blocks/products/cells/cells-cloud-parameters itName="password"  required="False" prompt="The password needed to open an Excel file.">}}
{{< blocks/products/cells/cells-cloud-parameters itName="checkExcelRestriction"  required="False" prompt="Whether check restriction of excel file when user modify cells related objects.">}}
{{< blocks/products/cells/cells-cloud-parameters itName="region"  required="False" prompt="The regional settings for workbook.">}} -->
{{< blocks/products/cells/cells-cloud-showparameters >}}
{{% blocks/products/cells/cells-cloud-showcode request="outFormat,mergeToOneSheet,password,checkExcelRestriction,region" requestvalue=",true,,true," %}}

```cs
	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Model;
	using Aspose.Cells.Cloud.SDK.Request;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
    var spreadsheets = new Dictionary<string, System.IO.Stream>
        {
            { "datasource1.xlsx", File.OpenRead("path/to/datasource1.xlsx") },
            { "datasource2.xlsx", File.OpenRead("path/to/datasource2.xlsx") }
        };
	cellsApi.MergeSpreadsheets(new MergeSpreadsheetsRequest { Spreadsheet = spreadsheets, outFormat = "pdf" }, "result.pdf");
```
{{% /blocks/products/cells/cells-cloud-showcode %}}
{{< /blocks/products/cells/cells-cloud-run-merge >}}

{{< blocks/products/cells/cells-cloud-available-sdks >}}




{{< /blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-resource-links >}}

{{< /blocks/products/pf/main-wrap-class >}}
