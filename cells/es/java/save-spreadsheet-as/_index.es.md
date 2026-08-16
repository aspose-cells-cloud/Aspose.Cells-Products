---
title: Convierte una hoja de cálculo en almacenamiento en la nube al formato especificado.
description: Este método accede a un archivo de hoja de cálculo directamente desde el almacenamiento en la nube, lo convierte al formato de salida deseado (p. ej., XLSX, PDF, CSV) y devuelve el resultado convertido sin descargar el archivo al sistema local. \nAsegúrese de que la configuración del almacenamiento en la nube (como credenciales de acceso y ruta del archivo) esté configurada correctamente. \nEl proceso de conversión ocurre completamente dentro del entorno de la nube, minimizando la sobrecarga de transferencia de datos y mejorando la seguridad al mantener los datos sensibles dentro de la infraestructura cloud. \nSi el archivo de origen no existe, o si ocurre un error durante el proceso de conversión, se lanzará una excepción apropiada. \nLos formatos de salida admitidos dependen de las capacidades del servicio de conversión subyacente.
kwords: aspose cells
url: /es/net/save-spreadsheet-as/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Funcionalidad de Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir archivos Excel a otros formatos" indexdesc="Aspose.Cells Cloud ofrece un soporte robusto para la conversión de formatos de archivos Excel, un proceso conocido por su complejidad. Aspose.Cells Cloud admite más de 30 formatos de archivo, incluidos Excel, PDF, Markdown, JSON, XML, CSV, HTML, entre otros." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Funciones compatibles" featuremsg="Aspose.Cells Cloud proporciona una API REST que soporta la conversión de archivos Excel a varios formatos y ofrece SDKs para múltiples lenguajes de programación. Estos lenguajes incluyen .NET, Java, Go, NodeJS, Python, entre otros." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/{name}/saveas"  %}}

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
            SaveSpreadsheetAsRequest request = new SaveSpreadsheetAsRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.SaveSpreadsheetAs(request);
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