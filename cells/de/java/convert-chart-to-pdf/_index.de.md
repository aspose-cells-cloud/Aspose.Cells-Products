---
title: Konvertiert ein Diagramm einer Tabellenkalkulation auf einem lokalen Laufwerk in PDF.
description: Diese Methode liest ein Diagramm einer Tabellenkalkulationsdatei aus dem lokalen Dateisystem, konvertiert es in das gewünschte PDF-Format und gibt das konvertierte Ergebnis zurück.\nDer Quell-Dateipfad und das Zielformat müssen korrekt angegeben werden.\nStellen Sie sicher, dass die erforderlichen Berechtigungen zum Lesen der Quelldatei und zum Schreiben der konvertierten Datei vorhanden sind, falls zutreffend.\nDer Konvertierungsprozess erfolgt vollständig auf dem Cloud-Server, wodurch die Notwendigkeit von Cloud‑Speicher oder externen Downloads entfällt.\nFalls die Quelldatei nicht existiert, nicht zugänglich ist oder ein Fehler während des Konvertierungsprozesses auftritt, wird eine entsprechende Ausnahme ausgelöst.\nUnterstützte Formate für die Konvertierung hängen von den verfügbaren Bibliotheken und deren Fähigkeiten ab.
kwords: aspose cells
url: /de/net/convert-chart-to-pdf/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud-Funktion" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel-Dateien in andere Formate konvertieren" indexdesc="Aspose.Cells Cloud bietet umfassende Unterstützung für die Konvertierung von Excel-Dateiformaten, ein Prozess, der für seine Komplexität bekannt ist. Aspose.Cells Cloud unterstützt mehr als 30 Dateiformate, darunter Excel, PDF, Markdown, JSON, XML, CSV, HTML und weitere." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Unterstützte Funktionen" featuremsg="Aspose.Cells Cloud stellt eine REST‑API bereit, die die Konvertierung von Excel‑Dateien in verschiedene Formate unterstützt und SDKs für mehrere Programmiersprachen bietet. Zu diesen Programmiersprachen gehören .NET, Java, Go, NodeJS, Python und weitere." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/chart/pdf"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="Das zu konvertierende Format (CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}} -->
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
            ConvertChartToImageRequest request = new ConvertChartToImageRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setchartIndex(0);
            api.ConvertChartToImage(request);
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