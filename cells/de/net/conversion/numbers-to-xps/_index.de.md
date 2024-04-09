---
title:  Konvertieren Sie NUMBERS mit C# in XPS
description:  Verwendung des Aspose.Cells Cloud SDK für C# zum Konvertieren einer Datei im NUMBERS-Format in eine Datei im XPS-Format.
kwords: Excel, Convert NUMBERS to XPS, REST, C#
howto: How to convert NUMBERS to XPS using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie NUMBERS in XPS" h2="C#-Bibliothek zum Konvertieren von NUMBERS in XPS" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Netzwerkprojekten zu erstellen. Dies ist eine professionelle Lösung, um NUMBERS online mit C# in XPS und andere Dokumentformate zu konvertieren." urlsection="conversion/numbers-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie NUMBERS in XPS mit dem Cloud SDK Cells für C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von NUMBERS in XPS kann eine komplexe Aufgabe sein. Unser C# SDK verarbeitet alle NUMBERS-Formatkonvertierungen in das XPS-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der Quell-NUMBERS-Tabelle bei. Unsere C#-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von NUMBERS-Dateien in XPS-Dateien. Dieses Cloud SDK bietet C#-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige XPS-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Codebeispiel für die Konvertierung von NUMBERS in XPS mithilfe des Cloud SDK Cells" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string format = "xps";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xps";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie NUMBERS mithilfe der Cloud Net-Bibliothek Cells in XPS konvertieren." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek C# und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in C#</li>
<li>Verwenden Sie die Methode `PutConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>NET Framework 4.5.2 oder neuer</li>
<li>Net Standard 2.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
