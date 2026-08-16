---
title: Convierte un gráfico de hoja de cálculo en una unidad local a PDF.
description: Este método lee un archivo de gráfico de hoja de cálculo del sistema de archivos local, lo convierte al formato PDF deseado y devuelve el resultado convertido. \nLa ruta del archivo fuente y el formato de destino deben especificarse correctamente. \nAsegúrese de que los permisos necesarios estén vigentes para leer el archivo fuente y escribir el archivo convertido, si corresponde. \nEl proceso de conversión ocurre totalmente en el servidor cloud, eliminando la necesidad de cualquier almacenamiento en la nube o descargas externas. \nSi el archivo fuente no existe, es inaccesible o ocurre un error durante el proceso de conversión, se lanzará una excepción adecuada. \nLos formatos admitidos para la conversión dependen de las bibliotecas disponibles y sus capacidades.
kwords: aspose cells
url: /es/net/convert-chart-to-pdf/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Funciones de Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir archivos de Excel a otros formatos" indexdesc="Aspose.Cells Cloud ofrece un soporte sólido para la conversión de formatos de archivos de Excel, un proceso conocido por su complejidad. Aspose.Cells Cloud admite más de 30 formatos de archivo, incluidos Excel, PDF, Markdown, Json, XML, Csv, Html, entre otros." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Funciones compatibles" featuremsg="Aspose.Cells Cloud proporciona una API REST que admite la conversión de archivos de Excel a varios formatos y ofrece SDKs para múltiples lenguajes de programación. Estos lenguajes incluyen .NET, Java, Go, NodeJS, Python, entre otros." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/chart/pdf"  %}}

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
            ConvertChartToImageRequest request = new ConvertChartToImageRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setchartIndex(0);
            api.ConvertChartToImage(request);
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