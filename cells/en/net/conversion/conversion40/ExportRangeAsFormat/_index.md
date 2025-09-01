---
title: Converts the range of spreadsheet in cloud storage to the specified format.
description: This method processes a range of spreadsheet directly in cloud storage, converting it to the requested output format (PDF, or Image format) without requiring the file to be downloaded to the local machine. \nThe operation relies on valid cloud storage credentials and an accessible file path or identifier. \nThe conversion is performed remotely, reducing data transfer and improving performance for large files. \nIf the source file is not found, access is denied, or an error occurs during conversion, an appropriate exception will be thrown. \nSupported output formats are determined by the capabilities of the underlying cloud conversion service.
kwords: aspose cells
url: /net/export-range-as-format/
---


{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convert Excel files to other formats" indexdesc="Aspose.Cells Cloud provides robust support for Excel file format conversion, a process known for its intricacy. Aspose.Cells Cloud supports 30+ file formats, including Excel, Pdf, Markdown, Json, XML, Csv, Html, and so on.">}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="Aspose.Cells Cloud provides REST API which supports converting Excel files to various format and offers SDKs for multiple programming languages. These programming languages are include of Net, Java, Go, NodeJS, Python, and so on. .">}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="/cells/{name}/worksheets/{worksheet}/ranges/{range}"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers).">}} -->
<!-- {{< blocks/products/cells/cells-cloud-showparameters >}} -->
{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}

```cs
	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Model;
	using Aspose.Cells.Cloud.SDK.Request;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
    cellsApi.ExportRangeAsFormat(new ExportRangeAsFormatRequest{ name = "EmployeeSalesSummary.xlsx", format = "pdf" }, "result.pdf");
```
{{% /blocks/products/cells/cells-cloud-showcode %}}
<!-- {{< /blocks/products/cells/cells-cloud-run-conversion >}} -->



{{< blocks/products/cells/cells-cloud-available-sdks >}}





{{< /blocks/products/pf/main-container >}}


{{< blocks/products/cells/cells-cloud-resource-links >}}
{{< /blocks/products/pf/main-wrap-class >}}
