---
title:  Konvertieren Sie HTML mit C# in ODS
description:  Verwendung des Aspose.Cells Cloud SDK für C# zum Konvertieren einer Datei im HTML-Format in eine Datei im ODS-Format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie HTML in ODS" h2="C#-Bibliothek zur Konvertierung von HTML in ODS" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Netzwerkprojekten zu erstellen. Dies ist eine professionelle Lösung, um HTML online mit C# in ODS und andere Dokumentformate zu konvertieren." urlsection="conversion/html-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie HTML in ODS mit dem Cloud SDK Cells für C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von HTML in ODS kann eine komplexe Aufgabe sein. Unser C# SDK übernimmt alle Konvertierungen von HTML in das ODS-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der Quelltabelle HTML bei. Unsere C#-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von HTML in ODS-Dateien. Dieses Cloud SDK bietet C#-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige ODS-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Codebeispiel für die Konvertierung von HTML in ODS mit Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.html";
    string format = "ods";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.ods";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK for Net zum Konvertieren von Excel-Dateien in andere Formate HTML in ODS" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `PutConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>NET Framework 4.5.2 oder neuer</li>
<li>Net Standard 2.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
