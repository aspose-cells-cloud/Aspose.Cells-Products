﻿---
title:  Speichern Sie NUMBERS als CSV mit Go
description:  Verwendung des Cloud SDK Aspose.Cells für Go zum Speichern der Datei im NUMBERS-Format als Datei im CSV-Format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="ZAHLEN als CSV speichern" h2="Gehen Sie zur Bibliothek, um ZAHLEN als CSV zu speichern" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Go zu erstellen. Dies ist eine professionelle Lösung, um ZAHLEN als CSV und andere Dokumentformate online mit Go zu speichern." urlsection="saveas/numbers-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine NUMBERS-Datei als CSV in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus NUMBERS als CSV ist eine komplexe Aufgabe. Alle Übergänge von NUMBERS zum CSV-Format werden von unserem Go SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der NUMBERS-Quelltabelle erhalten bleibt. Unsere Go-Bibliothek ist eine professionelle Lösung, um ZAHLEN online als CSV-Dateien zu speichern. Dieses Cloud SDK bietet Go-Entwicklern leistungsstarke Funktionalität und eine perfekte CSV-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Go-Codebeispiel zum Speichern von ZAHLEN als CSV mit REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.numbers"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.csv"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie das Cells Cloud SDK für Go, um Excel-Dateien in anderen Formaten als CSV zu speichern" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Go-Version go1.13.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
