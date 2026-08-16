---
title: Konvertiert ein Arbeitsblatt einer Tabellenkalkulation auf einem lokalen Laufwerk in das Bildformat.
description: Diese Methode liest eine Tabellenkalkulationsdatei vom lokalen Dateisystem, konvertiert ihr Arbeitsblatt in das gewünschte Bildformat (z. B. svg, png, …) und gibt das konvertierte Ergebnis zurück. \nDer Pfad zur Quelldatei und das Zielformat müssen korrekt angegeben werden. \nStellen Sie sicher, dass die erforderlichen Berechtigungen zum Lesen der Quelldatei und ggf. zum Schreiben der konvertierten Datei vorhanden sind. \nDer Konvertierungsprozess erfolgt vollständig auf dem Cloud‑Server, wodurch die Notwendigkeit für Cloud‑Speicher oder externe Downloads entfällt. \nWenn die Quelldatei nicht existiert, nicht zugänglich ist oder ein Fehler während des Konvertierungsprozesses auftritt, wird eine entsprechende Ausnahme ausgelöst. \nUnterstützte Formate für die Konvertierung hängen von den verfügbaren Bibliotheken und deren Fähigkeiten ab.
kwords: aspose cells
url: /de/net/convert-worksheet-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud-Funktion" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel-Dateien in andere Formate konvertieren" indexdesc="Aspose.Cells Cloud bietet robuste Unterstützung für die Konvertierung von Excel-Dateiformaten, ein als komplex bekannter Vorgang. Aspose.Cells Cloud unterstützt mehr als 30 Dateiformate, darunter Excel, Pdf, Markdown, Json, XML, Csv, Html und so weiter." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Unterstützte Funktionen" featuremsg="Aspose.Cells Cloud stellt eine REST-API bereit, die die Konvertierung von Excel-Dateien in verschiedene Formate unterstützt und SDKs für mehrere Programmiersprachen anbietet. Zu den unterstützten Programmiersprachen gehören .NET, Java, Go, NodeJS, Python und weitere." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/worksheet/image"  %}}

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
            ConvertWorksheetToImageRequest request = new ConvertWorksheetToImageRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setformat("png");
            api.ConvertWorksheetToImage(request);
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