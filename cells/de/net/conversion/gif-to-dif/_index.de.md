﻿---
title:  GIF in DIF Konvertieren Sie API für C#
description:  Cloud-APIs und SDKs für Microsoft Excel und OpenOffice Calc. Konvertieren Sie die Tabelle in ein anderes Dateiformat.
url: /de/net/conversion/gif-to-dif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API um GIF in DIF umzuwandeln" h2="C# Bibliothek zum Konvertieren von GIF in DIF" p="Verwenden Sie Cells Conversion REST API, um benutzerdefinierte Tabellenkalkulations-Workflows in Net zu erstellen. Dies ist eine professionelle Lösung, um GIF in DIF und andere Dokumentformate online mit C# zu konvertieren." urlsection="conversion/gif-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie eine GIF-Datei in C# in DIF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von GIF in DIF ist eine komplexe Aufgabe. Alle GIF-zu-DIF-Formatübergänge werden von unserem C# SDK durchgeführt, während der strukturelle und logische Hauptinhalt der GIF-Quelltabelle beibehalten wird. Unsere C#-Bibliothek ist eine professionelle Lösung zum Online-Konvertieren von GIF- in DIF-Dateien. Dieses Cloud-SDK bietet C#-Entwicklern leistungsstarke Funktionen und eine perfekte DIF-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in C# mit REST API zum Konvertieren von GIF in das DIF-Format" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.gif";
    string format = "dif";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.dif";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie C# API, um GIF in DIF zu konvertieren" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und API-Version</li>
<li>Rufen Sie die CellsWorkbookPutConvertWorkbook-Methode auf, um den resultierenden Stream abzurufen</li>
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