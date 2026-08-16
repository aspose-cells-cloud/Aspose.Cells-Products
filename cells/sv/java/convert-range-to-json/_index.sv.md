---
title: Konverterar ett område i ett kalkylblad på en lokal enhet till en json‑fil.
description: Denna metod läser en kalkylbladfil från det lokala filsystemet, konverterar dess område till önskad json‑fil och returnerar det konverterade resultatet. \nKällfilens sökväg och målformat måste specificeras korrekt. \nSäkerställ att nödvändiga behörigheter finns för att läsa källfilen och skriva den konverterade filen om tillämpligt. \nKonverteringsprocessen sker helt på molnservern, vilket eliminerar behovet av någon molnlagring eller externa nedladdningar. \nOm källfilen inte finns, är otillgänglig, eller om ett fel uppstår under konverteringsprocessen, kommer ett lämpligt undantag att kastas. \nStödda format för konvertering beror på tillgängliga bibliotek och deras kapabiliteter.
kwords: aspose cells
url: /sv/net/convert-range-to-json/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Konvertera Excel‑filer till andra format" indexdesc="Aspose.Cells Cloud erbjuder robust stöd för konvertering av Excel‑filformat, en process känd för sin komplexitet. Aspose.Cells Cloud stöder mer än 30 filformat, inklusive Excel, Pdf, Markdown, Json, XML, Csv, Html och så vidare." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Stödda funktioner" featuremsg="Aspose.Cells Cloud tillhandahåller ett REST‑API som stöder konvertering av Excel‑filer till olika format och erbjuder SDK:er för flera programmeringsspråk. Dessa programmeringsspråk inkluderar .NET, Java, Go, NodeJS, Python och så vidare." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/range/json"  %}}

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
            ConvertRangeToJsonRequest request = new ConvertRangeToJsonRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setrange("A1:C10");
            api.ConvertRangeToJson(request);
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