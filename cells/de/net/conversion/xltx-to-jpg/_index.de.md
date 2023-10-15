---
title:  Konvertieren Sie XLTX mit C# in JPG
description:  Verwendung des Aspose.Cells Cloud SDK für C# zum Konvertieren einer XLTX-Formatdatei in eine JPG-Formatdatei.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie XLTX in JPG" h2="C# Bibliothek zum Konvertieren von XLTX in JPG" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Netzwerkprojekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLTX in JPG und andere Dokumentformate unter C#." urlsection="conversion/xltx-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie XLTX in JPG mit dem Cloud SDK Cells für C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLTX in JPG kann eine komplexe Aufgabe sein. Unser C# SDK übernimmt alle XLTX-in-JPG-Formatkonvertierungen und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLTX-Quelltabelle bei. Unsere C#-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLTX- in JPG-Dateien. Dieses Cloud SDK bietet C#-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige JPG-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Codebeispiel für die Konvertierung von XLTX in JPG mit Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xltx";
    string format = "jpg";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.jpg";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK for Net, um Excel-Dateien in andere Formate, XLTX, JPG zu konvertieren" >}}
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
