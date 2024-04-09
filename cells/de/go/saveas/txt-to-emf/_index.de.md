---
title:  Speichern Sie TXT als EMF mit Go
description:  Verwendung des Aspose.Cells Cloud SDK für Go zum Speichern der TXT-Formatdatei als EMF-Formatdatei.
kwords: Excel, Save TXT as EMF, REST, Go
howto: How to save TXT as EMF using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie TXT unter EMF" h2="Gehen Sie zur Bibliothek, um TXT unter EMF zu speichern" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Go zu erstellen. Dies ist eine professionelle Lösung, um TXT als EMF und andere Dokumentformate online mit Go zu speichern." urlsection="saveas/txt-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine TXT-Datei unter dem Namen EMF in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus TXT als EMF ist eine komplexe Aufgabe. Alle TXT-Formatübergänge in das EMF-Format werden von unserem Go SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der TXT-Quelltabelle erhalten bleibt. Unsere Go-Bibliothek ist eine professionelle Lösung, um TXT-Dateien im Format EMF online zu speichern. Dieses Cloud SDK bietet Go-Entwicklern leistungsstarke Funktionalität und eine perfekte EMF-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go-Codebeispiel zum Speichern von TXT als EMF mit REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.txt"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.emf"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie TXT mithilfe der Cloud Go-Bibliothek Cells als EMF speichern." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Go-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in go.</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>go-Version go1.13.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
