﻿---
title:  Speichern Sie XLSM als SQL mit C#
description:  Verwendung des Cloud SDK Aspose.Cells für C# zum Speichern der XLSM-Formatdatei als SQL-Formatdatei.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Speichern Sie XLSM als SQL" h2="C# Bibliothek zum Speichern von XLSM als SQL" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Net zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von XLSM als SQL und anderen Dokumentformaten unter C#." urlsection="saveas/xlsm-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine XLSM-Datei als SQL unter C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus XLSM als SQL ist eine komplexe Aufgabe. Alle XLSM-zu-SQL-Formatübergänge werden von unserem SDK C# durchgeführt, während der strukturelle und logische Hauptinhalt der XLSM-Quelltabelle erhalten bleibt. Unsere C#-Bibliothek ist eine professionelle Lösung, um XLSM als SQL-Dateien online zu speichern. Dieses Cloud SDK bietet C# Entwicklern leistungsstarke Funktionalität und perfekte SQL-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Codebeispiel zum Speichern von XLSM als SQL mit REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsm";
    string newfilename = "Book1SaveAs.sql";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK for Net, um Excel-Dateien in anderen Formaten, XLSM als SQL, zu speichern" >}}
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
