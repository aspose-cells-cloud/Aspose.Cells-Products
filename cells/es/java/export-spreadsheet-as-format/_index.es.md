---
title: Convertir archivos de Excel a otros formatos.
description: Aspose.Cells Cloud proporciona un soporte robusto para la conversión de formatos de archivo de Excel, un proceso conocido por su complejidad. Aspose.Cells Cloud soporta más de 30 formatos de archivo, incluidos Excel, Pdf, Markdown, Json, XML, Csv, Html, y así sucesivamente.
kwords: aspose cells
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Funcionalidad de Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir archivos de Excel a otros formatos" indexdesc="Aspose.Cells Cloud proporciona un soporte robusto para la conversión de formatos de archivo de Excel, un proceso conocido por su complejidad. Aspose.Cells Cloud soporta más de 30 formatos de archivo, incluidos Excel, Pdf, Markdown, Json, XML, Csv, Html, y así sucesivamente.">}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Funciones compatibles" featuremsg="Aspose.Cells Cloud ofrece una API REST que permite convertir archivos de Excel a varios formatos y ofrece SDKs para múltiples lenguajes de programación. Estos lenguajes incluyen .NET, Java, Go, NodeJS, Python, entre otros.">}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="https://api.aspose.cloud/v4.0/cells/cells/{name}"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="EjecutarCódigo" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="El formato a convertir (CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}} -->
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
{{< /blocks/products/pf/main-wrap-class >}}