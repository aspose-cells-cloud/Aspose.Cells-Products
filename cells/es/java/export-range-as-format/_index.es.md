---
title: Convierte el rango de hoja de cálculo en almacenamiento en la nube al formato especificado.
description: Este método procesa un rango de hoja de cálculo directamente en el almacenamiento en la nube, convirtiéndolo al formato de salida solicitado (PDF o formato de imagen) sin requerir que el archivo se descargue en la máquina local.\nLa operación depende de credenciales válidas de almacenamiento en la nube y de una ruta de archivo o identificador accesible.\nLa conversión se realiza de forma remota, reduciendo la transferencia de datos y mejorando el rendimiento para archivos grandes.\nSi no se encuentra el archivo fuente, se niega el acceso o ocurre un error durante la conversión, se lanzará una excepción apropiada.\nLos formatos de salida compatibles se determinan por las capacidades del servicio de conversión en la nube subyacente.
kwords: aspose cells
url: /es/java/export-range-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir archivos de Excel a otros formatos" indexdesc="Aspose.Cells Cloud ofrece un soporte robusto para la conversión de formatos de archivos Excel, un proceso conocido por su complejidad. Aspose.Cells Cloud admite más de 30 formatos de archivo, incluidos Excel, Pdf, Markdown, Json, XML, Csv, Html, entre otros." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Características compatibles" featuremsg="Aspose.Cells Cloud proporciona una API REST que admite la conversión de archivos Excel a varios formatos y ofrece SDKs para múltiples lenguajes de programación. Estos lenguajes incluyen .Net, Java, Go, NodeJS, Python, entre otros. ." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="/cells/{name}/worksheets/{worksheet}/ranges/{range}"  %}}

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