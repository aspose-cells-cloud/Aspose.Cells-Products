---
title:  Speichern Sie XML als SQL mit C#
description:  Verwendung des Cloud SDK Aspose.Cells für C# zum Speichern der XML-Formatdatei als SQL-Formatdatei.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Speichern Sie XML als SQL" h2="C# Bibliothek zum Speichern von XML als SQL" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Net zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von XML als SQL und anderen Dokumentformaten unter C#." urlsection="saveas/xml-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine XML-Datei als SQL in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus XML als SQL ist eine komplexe Aufgabe. Alle XML-zu-SQL-Formatübergänge werden von unserem SDK C# durchgeführt, wobei der strukturelle und logische Hauptinhalt der XML-Quelltabelle erhalten bleibt. Unsere C#-Bibliothek ist eine professionelle Lösung, um XML als SQL-Dateien online zu speichern. Dieses Cloud SDK bietet C# Entwicklern leistungsstarke Funktionalität und perfekte SQL-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Codebeispiel zum Speichern von XML als SQL mit REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xml";
    string newfilename = "Book1SaveAs.sql";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK for Net, um Excel-Dateien in anderen Formaten wie XML und SQL zu speichern" >}}
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
