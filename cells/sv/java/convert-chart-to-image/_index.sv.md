---
title: Konverterar ett diagram i kalkylblad på en lokal enhet till bild.
description: Denna metod läser ett diagram i kalkylbladsfil från det lokala filsystemet, konverterar det till önskat bildformat (t.ex. PNG, SVG, Tiff) och returnerar det konverterade resultatet. \nKällfilens sökväg och målformat måste specificeras korrekt. \nSe till att nödvändiga behörigheter finns för att läsa källfilen och skriva den konverterade filen om tillämpligt. \nKonverteringsprocessen sker helt på molnservern, vilket eliminerar behovet av någon molnlagring eller externa nedladdningar. \nOm källfilen inte finns, är otillgänglig eller om ett fel uppstår under konverteringsprocessen, kommer ett lämpligt undantag att kastas. \nStödda format för konvertering beror på de tillgängliga biblioteken och deras kapacitet.
kwords: aspose cells
url: /sv/java/convert-chart-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud-funktion" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Konvertera Excel-filer till andra format" indexdesc="Aspose.Cells Cloud erbjuder robust stöd för konvertering av Excel-filformat, en process som är känd för sin komplexitet. Aspose.Cells Cloud stöder mer än 30 filformat, inklusive Excel, Pdf, Markdown, Json, XML, Csv, Html och så vidare." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="Aspose.Cells Cloud tillhandahåller ett REST API som stödjer konvertering av Excel-filer till olika format och erbjuder SDK:er för flera programmeringsspråk. Dessa programmeringsspråk inkluderar .Net, Java, Go, NodeJS, Python och så vidare." >}}
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