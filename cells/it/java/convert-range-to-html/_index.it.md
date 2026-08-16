---
title: Converte un intervallo di foglio di calcolo su un disco locale in un file html.
description: Questo metodo legge un file di foglio di calcolo dal file system locale, converte l'intervallo desiderato nel file HTML richiesto e restituisce il risultato convertito.\nIl percorso del file di origine e il formato di destinazione devono essere specificati correttamente.\nAssicurarsi che le autorizzazioni necessarie siano presenti per leggere il file di origine e scrivere il file convertito, se applicabile.\nIl processo di conversione avviene interamente sul server cloud, eliminando la necessità di archiviazione cloud o download esterni.\nSe il file di origine non esiste, è inaccessibile o si verifica un errore durante il processo di conversione, verrà generata un'eccezione appropriata.\nI formati supportati per la conversione dipendono dalle librerie disponibili e dalle loro capacità.
kwords: aspose cells
url: /it/java/convert-range-to-html/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Funzionalità Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Converti file Excel in altri formati" indexdesc="Aspose.Cells Cloud offre un supporto robusto per la conversione del formato dei file Excel, un processo noto per la sua complessità. Aspose.Cells Cloud supporta più di 30 formati di file, tra cui Excel, PDF, Markdown, JSON, XML, CSV, HTML e così via.">}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Funzionalità supportate" featuremsg="Aspose.Cells Cloud fornisce un'API REST che supporta la conversione di file Excel in vari formati e offre SDK per più linguaggi di programmazione. Questi linguaggi includono .NET, Java, Go, NodeJS, Python e così via." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/range/html"  %}}

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
            ConvertRangeToHtmlRequest request = new ConvertRangeToHtmlRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setrange("A1:C10");
            api.ConvertRangeToHtml(request);
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