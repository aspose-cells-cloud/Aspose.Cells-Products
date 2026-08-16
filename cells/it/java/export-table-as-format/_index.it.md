---
title: Converte una tabella di foglio di calcolo nello storage cloud nel formato specificato.
description: Questo metodo elabora una tabella di foglio di calcolo direttamente nello storage cloud, convertendola nel formato di output richiesto (PDF o formato immagine) senza richiedere il download del file sulla macchina locale. \nL'operazione si basa su credenziali di storage cloud valide e su un percorso o identificatore di file accessibile. \nLa conversione avviene remotamente, riducendo il trasferimento dei dati e migliorando le prestazioni per file di grandi dimensioni. \nSe il file sorgente non viene trovato, l'accesso è negato o si verifica un errore durante la conversione, verrà sollevata un'eccezione appropriata. \nI formati di output supportati sono determinati dalle capacità del servizio di conversione cloud sottostante.
kwords: aspose cells
url: /it/java/export-table-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Converti file Excel in altri formati" indexdesc="Aspose.Cells Cloud offre un supporto solido per la conversione del formato file Excel, un processo noto per la sua complessità. Aspose.Cells Cloud supporta più di 30 formati di file, inclusi Excel, PDF, Markdown, JSON, XML, CSV, HTML e così via." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Funzionalità supportate" featuremsg="Aspose.Cells Cloud fornisce un'API REST che supporta la conversione dei file Excel in vari formati e offre SDK per più linguaggi di programmazione. Questi linguaggi includono .NET, Java, Go, NodeJS, Python e così via." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="/cells/{name}/worksheets/{worksheet}/tables/{tableName}"  %}}

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
            ExportTableAsFormatRequest request = new ExportTableAsFormatRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.ExportTableAsFormat(request);
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