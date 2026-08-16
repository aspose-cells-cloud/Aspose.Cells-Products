---
title: Konverterar ett område av kalkylblad på en lokal enhet till CSV‑filen.
description: Denna metod läser en kalkylbladsfil från det lokala filsystemet, konverterar dess område till den önskade CSV‑filen och returnerar det konverterade resultatet. Källfilens sökväg och målformat måste anges korrekt. Säkerställ att nödvändiga behörigheter finns för att läsa källfilen och skriva den konverterade filen om tillämpligt. Konverteringsprocessen sker helt på molnservern, vilket eliminerar behovet av någon molnlagring eller externa nedladdningar. Om källfilen inte finns, är otillgänglig, eller om ett fel uppstår under konverteringsprocessen, kommer ett lämpligt undantag att kastas. Format som stöds för konvertering beror på de tillgängliga biblioteken och deras möjligheter.
kwords: aspose celler
url: /sv/net/convert-range-to-csv/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud-funktion" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Konvertera Excel-filer till andra format" indexdesc="Aspose.Cells Cloud erbjuder robust stöd för konvertering av Excel‑filformat, en process känd för sin komplexitet. Aspose.Cells Cloud stöder över 30 filformat, inklusive Excel, Pdf, Markdown, Json, XML, Csv, Html och så vidare." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Stödda funktioner" featuremsg="Aspose.Cells Cloud tillhandahåller ett REST‑API som stödjer konvertering av Excel‑filer till olika format och erbjuder SDK‑er för flera programmeringsspråk. Dessa programmeringsspråk inkluderar .NET, Java, Go, NodeJS, Python och så vidare." >}}
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
{{< /blocks/products/pf/main-wrap-class >}}