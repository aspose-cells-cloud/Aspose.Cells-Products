---
title: Konvertiert ein Diagramm einer Tabellenkalkulation auf einem lokalen Laufwerk in ein Bild.
description: Diese Methode liest ein Diagramm einer Tabellenkalkulationsdatei vom lokalen Dateisystem, konvertiert es in das gewünschte Bildformat (z. B. PNG, SVG, Tiff) und gibt das konvertierte Ergebnis zurück. \nDer Pfad zur Quelldatei und das Zielformat müssen korrekt angegeben werden. \nStellen Sie sicher, dass die notwendigen Berechtigungen vorhanden sind, um die Quelldatei zu lesen und die konvertierte Datei bei Bedarf zu schreiben. \nDer Konvertierungsprozess erfolgt vollständig auf dem Cloud‑Server, wodurch die Notwendigkeit für Cloud‑Speicher oder externe Downloads entfällt. \nWenn die Quelldatei nicht existiert, nicht zugänglich ist oder während des Konvertierungsprozesses ein Fehler auftritt, wird eine entsprechende Ausnahme ausgelöst. \nUnterstützte Formate für die Konvertierung hängen von den verfügbaren Bibliotheken und deren Fähigkeiten ab.
kwords: aspose cells
url: /de/java/convert-chart-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convert Excel files to other formats" indexdesc="Aspose.Cells Cloud provides robust support for Excel file format conversion, a process known for its intricacy. Aspose.Cells Cloud supports 30+ file formats, including Excel, Pdf, Markdown, Json, XML, Csv, Html, and so on.">}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="Aspose.Cells Cloud provides REST API which supports converting Excel files to various format and offers SDKs for multiple programming languages. These programming languages are include of Net, Java, Go, NodeJS, Python, and so on. .">}}
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