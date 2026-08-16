---
title: Konvertiert eine Tabelle einer Kalkulationstabelle im Cloud‑Speicher in das angegebene Format.
description: Diese Methode verarbeitet eine Tabelle einer Kalkulationstabelle direkt im Cloud‑Speicher und konvertiert sie in das angeforderte Ausgabeformat (PDF oder Bildformat), ohne dass die Datei auf den lokalen Rechner heruntergeladen werden muss. \nDer Vorgang basiert auf gültigen Cloud‑Speicher‑Anmeldeinformationen und einem zugänglichen Dateipfad oder Identifier. \nDie Konvertierung wird remote ausgeführt, wodurch Datenübertragungen reduziert und die Leistung bei großen Dateien verbessert wird. \nWird die Quelldatei nicht gefunden, der Zugriff verweigert oder tritt während der Konvertierung ein Fehler auf, wird eine entsprechende Ausnahme ausgelöst. \nUnterstützte Ausgabeformate werden durch die Fähigkeiten des zugrunde liegenden Cloud‑Konvertierungsdienstes bestimmt.
kwords: aspose cells
url: /de/java/export-table-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel-Dateien in andere Formate konvertieren" indexdesc="Aspose.Cells Cloud bietet umfassende Unterstützung für die Konvertierung von Excel-Dateiformaten, ein Prozess, der für seine Komplexität bekannt ist. Aspose.Cells Cloud unterstützt mehr als 30 Dateiformate, darunter Excel, PDF, Markdown, JSON, XML, CSV, HTML und weitere." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Unterstützte Funktionen" featuremsg="Aspose.Cells Cloud bietet eine REST‑API, die die Konvertierung von Excel‑Dateien in verschiedene Formate unterstützt und SDKs für mehrere Programmiersprachen bereitstellt. Zu den unterstützten Programmiersprachen gehören .NET, Java, Go, NodeJS, Python und weitere." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="/cells/{name}/worksheets/{worksheet}/tables/{tableName}"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="Das Format, in das konvertiert werden soll (CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}} -->
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
{{< /blocks/products/pf/main-wrap-class >}}