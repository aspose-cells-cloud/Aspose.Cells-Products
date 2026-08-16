---
title: Convierte un rango de hoja de cálculo en una unidad local a un archivo csv.
description: Este método lee un archivo de hoja de cálculo del sistema de archivos local, convierte su rango al archivo csv deseado y devuelve el resultado convertido. La ruta del archivo fuente y el formato de destino deben especificarse correctamente. Asegúrese de que los permisos necesarios estén en su lugar para leer el archivo fuente y escribir el archivo convertido, si corresponde. El proceso de conversión ocurre completamente en el servidor en la nube, eliminando la necesidad de cualquier almacenamiento en la nube o descargas externas. Si el archivo fuente no existe, es inaccesible, o si ocurre un error durante el proceso de conversión, se lanzará una excepción apropiada. Los formatos compatibles para la conversión dependen de las bibliotecas disponibles y sus capacidades.
kwords: aspose cells
url: /es/net/convert-range-to-csv/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Funcionalidad de Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir archivos Excel a otros formatos" indexdesc="Aspose.Cells Cloud ofrece un soporte robusto para la conversión de formatos de archivos Excel, un proceso conocido por su complejidad. Aspose.Cells Cloud admite más de 30 formatos de archivo, incluidos Excel, Pdf, Markdown, Json, XML, Csv, Html, entre otros." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Características compatibles" featuremsg="Aspose.Cells Cloud proporciona una API REST que permite convertir archivos Excel a varios formatos y ofrece SDKs para múltiples lenguajes de programación. Estos lenguajes incluyen .NET, Java, Go, NodeJS, Python, entre otros." >}}
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