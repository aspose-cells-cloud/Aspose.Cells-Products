﻿---
title:  Speichern Sie SXC als CSV mit C#
description:  Verwenden des Aspose.Cells Cloud SDK für C#, um eine Datei im SXC-Format als Datei im CSV-Format zu speichern.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Speichern Sie SXC als CSV" h2="C# Bibliothek zum Speichern von SXC als CSV" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Net zu erstellen. Dies ist eine professionelle Lösung, um SXC als CSV und andere Dokumentformate online mit C# zu speichern." urlsection="saveas/sxc-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine SXC-Datei als CSV unter C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus SXC als CSV ist eine komplexe Aufgabe. Alle Übergänge vom SXC- zum CSV-Format werden von unserem SDK C# durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quell-SXC-Tabelle erhalten bleibt. Unsere C#-Bibliothek ist eine professionelle Lösung, um SXC als CSV-Dateien online zu speichern. Dieses Cloud SDK bietet C# Entwicklern leistungsstarke Funktionalität und perfekte CSV-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Codebeispiel zum Speichern von SXC als CSV mit REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.sxc";
    string newfilename = "Book1SaveAs.csv";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Net, um Excel-Dateien in anderen Formaten zu speichern: SXC als CSV" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
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
