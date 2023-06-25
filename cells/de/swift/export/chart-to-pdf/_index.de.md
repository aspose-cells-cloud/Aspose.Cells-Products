---
title:  Exportieren Sie CHART aus der Tabellenkalkulation nach PDF mit Swift API
description:  Aspose.Cells Cloud REST API unterstützt den Export von Excel Dateien und internen Objekten in verschiedene Formatdateien. SDK unterstützt verschiedene Entwicklungssprachen. Dazu gehören Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby und Swift.
url: /de/swift/export/chart-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API zum Exportieren von CHART in die Datei PDF" h2="Swift-Bibliothek zum Exportieren von CHART in die Datei PDF" p="Verwenden Sie Cells Export REST API, um Arbeitsabläufe interner Tabellenkalkulationsobjekte in Swift zu exportieren. Dies ist eine professionelle Lösung, um CHART online mit Swift aus einer Tabellenkalkulation in das Format PDF zu exportieren." urlsection="export/chart-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportieren Sie das CHART-Objekt in eine Datei im Format PDF in Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines CHART-Objekts aus einer Tabellenkalkulation in die Datei PDF ist eine komplexe Aufgabe. Der Export von CHART-Formatübergängen in das PDF-Format wird von unserem Swift SDK durchgeführt, während der strukturelle und logische Hauptinhalt der CHART-Quelltabelle erhalten bleibt. Unsere Swift-Bibliothek ist eine professionelle Lösung zum Online-Export von CHART-Objekten in Dateien im Format PDF. Dieses Cloud SDK bietet Swift-Entwicklern leistungsstarke Funktionalität und eine perfekte PDF-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in Swift mit REST API zum Exportieren von CHART in das Format PDF aus der Tabellenkalkulation" gistPath="" %}}
  
```swift
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-swift/
    import AsposeCellsCloud
    let expectation1 = self.expectation(description: "checkAuth")
    AsposeCellsCloudAPI.clientId = "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"
    AsposeCellsCloudAPI.clientSecret = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
    AuthAspose.checkAuth()
    {
        (authError) in
        guard authError == nil else {
            XCTFail("error checkAuth")
            return
        }
        expectation1.fulfill()
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
    let expectation = self.expectation(description: "testpostExport_Workbook")
    let objectType:String = "chart"
    let format:String = "pdf"
    var files = Dictionary<String, URL>()
    files[BOOK1] = getURL(BOOK1)
    files[MYDOC] = getURL(MYDOC)        
    LiteCellsAPI.postExport(files: files, objectType: objectType, format: format)
    {
        (response, error) in
        guard error == nil else {
            XCTFail("error testpostExport_Workbook")
            return
        }        
        if let response = response {
            XCTAssertTrue(response is FilesResult)
            expectation.fulfill()
        }
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Swift API, um CHART nach PDF zu exportieren" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und Version API</li>
<li>Rufen Sie die Methode postExport auf, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
