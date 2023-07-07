---
title:  EMF in TIFF Konvertieren Sie API für Swift
description:  Verwenden Sie das Cloud SDK Aspose.Cells für Swift, um eine Datei im Format EMF in eine Datei im Format TIFF zu konvertieren.
url: /de/swift/conversion/emf-to-tiff/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API zum Konvertieren von EMF in TIFF" h2="Swift-Bibliothek zum Konvertieren von EMF in TIFF" p="Verwenden Sie Cells Conversion REST API, um benutzerdefinierte Tabellenkalkulations-Workflows in Swift zu erstellen. Dies ist eine professionelle Lösung, um EMF in TIFF und andere Dokumentformate online mit Swift zu konvertieren." urlsection="conversion/emf-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie eine EMF-Datei in Swift in TIFF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von EMF in TIFF ist eine komplexe Aufgabe. Alle Formatübergänge von EMF zu TIFF werden von unserem Swift SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quelltabelle EMF erhalten bleibt. Unsere Swift-Bibliothek ist eine professionelle Lösung zum Online-Konvertieren von EMF- in TIFF-Dateien. Dieses Cloud SDK bietet Swift-Entwicklern leistungsstarke Funktionalität und eine perfekte TIFF-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in Swift mit REST API zum Konvertieren des Formats EMF in das Format TIFF" gistPath="" %}}
 
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
    let expectation = self.expectation(description: "PutConvert")
    let workbook:String = "Book1.emf"
    let format:String? = "tiff"     
    let url1: URL? = getURL(workbook)
    let filedata = NSData(contentsOfFile: url1!.path)
    let password:String? = nil
    let outPath:String? = nil
    CellsAPI.cellsWorkbookPutConvertWorkbook(file: url1!, format: format, password: password, outPath: outPath)
    {
        (response, error) in
        guard error == nil else {
            let errorinfo = self.GetErrorDataInfo(error: error as! ErrorResponse)
            print("error info: \(errorinfo!)")
            XCTFail("error PutConvert")
            return
        }            
        if let response = response {
            //response is a Data of file, we may write it down and check it.
            let fileName = "dest.tiff"
            let filePath = NSHomeDirectory()
            let fileManager = FileManager.default
            let path = "\(filePath)/tmp/\(fileName)"
            fileManager.createFile(atPath: path, contents:nil, attributes:nil)
            let handle = FileHandle(forWritingAtPath:path)
            handle?.write(response as Data)
            expectation.fulfill()
        }
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Swift API, um EMF in TIFF zu konvertieren" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und Version API</li>
<li>Rufen Sie die Methode „cellsWorkbookPutConvertWorkbook“ auf, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>macOS Monterey 12.4</li>
<li>Swift 4.2</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
