---
title: Excel dosyalarını diğer formatlara dönüştürün.
description: Aspose.Cells Cloud, karmaşıklığıyla bilinen Excel dosya formatı dönüşümüne güçlü destek sağlar. Aspose.Cells Cloud, Excel, Pdf, Markdown, Json, XML, Csv, Html ve benzeri dahil 30+ dosya formatını destekler.
kwords: aspose hücreler
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Özelliği" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel dosyalarını diğer formatlara dönüştürün" indexdesc="Aspose.Cells Cloud, karmaşıklığıyla bilinen Excel dosya formatı dönüşümüne güçlü destek sağlar. Aspose.Cells Cloud, Excel, Pdf, Markdown, Json, XML, Csv, Html ve benzeri dahil 30+ dosya formatını destekler." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Desteklenen Özellikler" featuremsg="Aspose.Cells Cloud, Excel dosyalarını çeşitli formatlara dönüştüren REST API'si sunar ve birçok programlama dili için SDK'lar sağlar. Bu programlama dilleri arasında .NET, Java, Go, NodeJS, Python vb. bulunur." >}}
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