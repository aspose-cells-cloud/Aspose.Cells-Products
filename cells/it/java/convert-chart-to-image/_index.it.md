---
title: Converte un grafico di foglio di calcolo su un'unità locale in immagine.
description: Questo metodo legge un grafico di un file di foglio di calcolo dal file system locale, lo converte nel formato immagine desiderato (ad es., PNG, SVG, TIFF) e restituisce il risultato convertito. \nIl percorso del file di origine e il formato di destinazione devono essere specificati correttamente. \nAssicurarsi che le autorizzazioni necessarie siano presenti per leggere il file di origine e scrivere il file convertito, se applicabile. \nIl processo di conversione avviene interamente sul server cloud, eliminando la necessità di alcuna archiviazione cloud o download esterni. \nSe il file di origine non esiste, è inaccessibile, o si verifica un errore durante il processo di conversione, verrà generata un'eccezione appropriata. \nI formati supportati per la conversione dipendono dalle librerie disponibili e dalle loro capacità.
kwords: aspose cells
url: /it/java/convert-chart-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Converti file Excel in altri formati" indexdesc="Aspose.Cells Cloud fornisce un supporto robusto per la conversione del formato dei file Excel, un processo noto per la sua complessità. Aspose.Cells Cloud supporta oltre 30 formati di file, tra cui Excel, Pdf, Markdown, Json, XML, Csv, Html e così via." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Funzionalità supportate" featuremsg="Aspose.Cells Cloud fornisce un'API REST che supporta la conversione di file Excel in vari formati e offre SDK per più linguaggi di programmazione. Questi linguaggi di programmazione includono .Net, Java, Go, NodeJS, Python e così via." >}}
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