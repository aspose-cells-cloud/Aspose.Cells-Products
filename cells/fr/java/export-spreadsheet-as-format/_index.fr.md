---
title: Convertir des fichiers Excel en d’autres formats.
description: Aspose.Cells Cloud offre une prise en charge robuste de la conversion des formats de fichiers Excel, un processus reconnu pour sa complexité. Aspose.Cells Cloud supporte plus de 30 formats de fichiers, y compris Excel, PDF, Markdown, JSON, XML, CSV, HTML, etc.
kwords: aspose cells
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Fonctionnalité Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir des fichiers Excel en d’autres formats" indexdesc="Aspose.Cells Cloud offre une prise en charge robuste de la conversion des formats de fichiers Excel, un processus reconnu pour sa complexité. Aspose.Cells Cloud supporte plus de 30 formats de fichiers, y compris Excel, PDF, Markdown, JSON, XML, CSV, HTML, etc." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Fonctionnalités prises en charge" featuremsg="Aspose.Cells Cloud fournit une API REST qui prend en charge la conversion de fichiers Excel vers divers formats et propose des SDK pour plusieurs langages de programmation. Ces langages incluent .NET, Java, Go, NodeJS, Python, etc." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="https://api.aspose.cloud/v4.0/cells/cells/{name}"  %}}

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
{{< blocks/products/pf/main-wrap-class >}}