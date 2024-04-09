---
title:  Konvertieren Sie ODS mit C# in PNG
description:  Verwendung des Aspose.Cells Cloud SDK für C# zum Konvertieren einer Datei im ODS-Format in eine Datei im PNG-Format.
kwords: Excel, Convert ODS to PNG, REST, C#
howto: How to convert ODS to PNG using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie ODS in PNG" h2="C#-Bibliothek zur Konvertierung von ODS in PNG" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Netzwerkprojekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von ODS in PNG und andere Dokumentformate unter Verwendung von C#." urlsection="conversion/ods-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie ODS in PNG mit dem Cloud SDK Cells für C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von ODS in PNG kann eine komplexe Aufgabe sein. Unser C# SDK übernimmt alle Konvertierungen von ODS in das PNG-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der Quell-ODS-Tabelle bei. Unsere C#-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von ODS- in PNG-Dateien. Dieses Cloud SDK bietet C#-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige PNG-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Codebeispiel für die Konvertierung von ODS in PNG mithilfe des Cloud SDK Cells" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.ods";
    string format = "png";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.png";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie ODS mithilfe der Cloud Net-Bibliothek Cells in PNG konvertieren." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek C# und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in C#</li>
<li>Verwenden Sie die Methode `PutConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>NET Framework 4.5.2 oder neuer</li>
<li>Net Standard 2.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
