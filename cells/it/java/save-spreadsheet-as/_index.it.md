---
title: Converti un foglio di calcolo nello storage cloud nel formato specificato.
description: Questo metodo accede a un file di foglio di calcolo direttamente dallo storage cloud, lo converte nel formato di output desiderato (ad es., XLSX, PDF, CSV) e restituisce il risultato convertito senza scaricare il file sul sistema locale. \nAssicurati che la configurazione dello storage cloud (come credenziali di accesso e percorso del file) sia impostata correttamente. \nIl processo di conversione avviene interamente nell'ambiente cloud, riducendo al minimo il carico di trasferimento dati e migliorando la sicurezza mantenendo i dati sensibili all'interno dell'infrastruttura cloud. \nSe il file di origine non esiste, o se si verifica un errore durante il processo di conversione, verrà generata un'eccezione appropriata. \nI formati di output supportati dipendono dalle capacità del servizio di conversione sottostante.
kwords: aspose cells
url: /it/net/save-spreadsheet-as/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Converti file Excel in altri formati" indexdesc="Aspose.Cells Cloud offre un supporto robusto per la conversione di formati di file Excel, un processo noto per la sua complessità. Aspose.Cells Cloud supporta oltre 30 formati di file, tra cui Excel, Pdf, Markdown, Json, XML, Csv, Html e così via." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Funzionalità supportate" featuremsg="Aspose.Cells Cloud fornisce una REST API che supporta la conversione di file Excel in vari formati e offre SDK per più linguaggi di programmazione. Questi linguaggi includono .Net, Java, Go, NodeJS, Python e così via." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/{name}/saveas"  %}}

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="Il formato da convertire (CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}} -->
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