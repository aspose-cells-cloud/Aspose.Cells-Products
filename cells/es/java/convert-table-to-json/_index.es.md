---
title: Convierte una tabla de una hoja de cálculo en una unidad local a un archivo json.
description: Este método lee un archivo de hoja de cálculo del sistema de archivos local, convierte su tabla al archivo html deseado y devuelve el resultado convertido. \nLa ruta del archivo de origen y el formato de destino deben especificarse correctamente. \nAsegúrese de que los permisos necesarios estén habilitados para leer el archivo de origen y escribir el archivo convertido, si corresponde. \nEl proceso de conversión se realiza completamente en el servidor en la nube, eliminando la necesidad de cualquier almacenamiento en la nube o descargas externas. \nSi el archivo de origen no existe, es inaccesible, o ocurre un error durante el proceso de conversión, se lanzará una excepción apropiada. \nLos formatos admitidos para la conversión dependen de las bibliotecas disponibles y sus capacidades.
kwords: aspose cells
url: /es/net/convert-table-to-json/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Funcionalidad de Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir archivos Excel a otros formatos" indexdesc="Aspose.Cells Cloud ofrece un soporte sólido para la conversión de formatos de archivos Excel, un proceso conocido por su complejidad. Aspose.Cells Cloud es compatible con más de 30 formatos de archivo, incluidos Excel, Pdf, Markdown, Json, XML, Csv, Html, entre otros." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Características compatibles" featuremsg="Aspose.Cells Cloud proporciona una API REST que admite la conversión de archivos Excel a varios formatos y ofrece SDKs para múltiples lenguajes de programación. Estos lenguajes de programación incluyen .NET, Java, Go, NodeJS, Python, entre otros." >}}
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