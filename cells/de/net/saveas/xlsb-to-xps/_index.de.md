---
title:  Speichern Sie XLSB als XPS mit C#
description:  Verwendung des Cloud SDK Aspose.Cells für C# zum Speichern der Datei im XLSB-Format als Datei im Format XPS.
kwords: Excel, Save XLSB as XPS, REST, C#
howto: How to save XLSB as XPS using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie XLSB unter XPS" h2="C#-Bibliothek zum Speichern von XLSB als XPS" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Net zu erstellen. Dies ist eine professionelle Lösung, um XLSB als XPS und andere Dokumentformate online unter C# zu speichern." urlsection="saveas/xlsb-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine XLSB-Datei als XPS in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus XLSB als XPS ist eine komplexe Aufgabe. Alle XLSB-Formatübergänge in das XPS-Format werden von unserem C#-SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der XLSB-Quelltabelle erhalten bleibt. Unsere C#-Bibliothek ist eine professionelle Lösung, um XLSB als XPS-Dateien online zu speichern. Dieses Cloud SDK bietet C# Entwicklern leistungsstarke Funktionalität und eine perfekte XPS Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Codebeispiel zum Speichern von XLSB als XPS mit REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsb";
    string newfilename = "Book1SaveAs.xps";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie XLSB mithilfe der Cloud Net-Bibliothek Cells als XPS speichern." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek C# und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in C#</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>NET Framework 4.5.2 oder neuer</li>
<li>Net Standard 2.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
