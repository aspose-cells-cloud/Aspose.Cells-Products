---
title:  Speichern Sie XLSB als MHTML mit Go
description:  Verwendung von Aspose.Cells Cloud SDK für Go zum Speichern von XLSB-Formatdateien als MHTML-Formatdateien.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSB als MHTML speichern" h2="Go-Bibliothek zum Speichern von XLSB als MHTML" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Go zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von XLSB als MHTML und anderen Dokumentformaten mit Go." urlsection="saveas/xlsb-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine XLSB-Datei als MHTML in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten von XLSB als MHTML ist eine komplexe Aufgabe. Alle XLSB-zu-MHTML-Formatübergänge werden von unserem Go SDK durchgeführt, während die wichtigsten strukturellen und logischen Inhalte der XLSB-Quelltabelle erhalten bleiben. Unsere Go-Bibliothek ist eine professionelle Lösung, um XLSB als MHTML-Dateien online zu speichern. Dieses Cloud SDK bietet Go-Entwicklern leistungsstarke Funktionalität und perfekte MHTML-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Go-Codebeispiel zum Speichern von XLSB als MHTML mit REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.xlsb"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.mhtml"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Go, um Excel-Dateien in anderen Formaten, XLSB und MHTML zu speichern" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>go-Version go1.13.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
