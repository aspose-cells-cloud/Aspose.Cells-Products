---
title: Convierte un gráfico de hoja de cálculo en una unidad local a imagen.
description: Este método lee un gráfico de un archivo de hoja de cálculo del sistema de archivos local, lo convierte al formato de imagen deseado (p. ej., PNG, SVG, Tiff) y devuelve el resultado convertido. \nLa ruta del archivo de origen y el formato de destino deben especificarse correctamente. \nAsegúrese de que los permisos necesarios estén disponibles para leer el archivo de origen y escribir el archivo convertido si corresponde. \nEl proceso de conversión se realiza completamente en el servidor en la nube, eliminando la necesidad de cualquier almacenamiento en la nube o descargas externas. \nSi el archivo de origen no existe, no es accesible, o ocurre un error durante el proceso de conversión, se lanzará una excepción apropiada. \nLos formatos admitidos para la conversión dependen de las bibliotecas disponibles y sus capacidades.
kwords: aspose cells
url: /es/java/convert-chart-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Características de Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir archivos de Excel a otros formatos" indexdesc="Aspose.Cells Cloud ofrece un soporte robusto para la conversión de formatos de archivos de Excel, un proceso conocido por su complejidad. Aspose.Cells Cloud soporta más de 30 formatos de archivo, incluidos Excel, Pdf, Markdown, Json, XML, Csv, Html, entre otros." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Funciones compatibles" featuremsg="Aspose.Cells Cloud proporciona una API REST que permite convertir archivos de Excel a varios formatos y ofrece SDKs para múltiples lenguajes de programación. Estos lenguajes de programación incluyen .Net, Java, Go, NodeJS, Python, entre otros." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/chart/image"  %}}

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
            request.setformat("png");
            api.ConvertChartToImage(request);
        } catch (ApiException e) {
            e.printStackTrace();
        }
    }
}
```

{{% /blocks/products/cells/cells-cloud-showcode %}}



{{< blocks/products/cells/cells-cloud-available-sdks >}}





{{< /blocks/products/pf/main-container >}}


{{< blocks/products/cells/cells-cloud-resource-links >}}
{{< /blocks/products/pf/main-wrap-class >}}