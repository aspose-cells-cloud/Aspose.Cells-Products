﻿---
title:  Converti GIF in PPTX API per Swift
description:  Utilizzo di Aspose.Cells Cloud SDK per Swift per convertire il file in formato GIF in un file in formato PPTX.
url: /it/swift/conversion/gif-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API per convertire GIF in PPTX" h2="Libreria Swift per convertire GIF in PPTX" p="Utilizza Cells Conversion REST API per creare flussi di lavoro personalizzati per fogli di calcolo in Swift. Questa è una soluzione professionale per convertire GIF in PPTX e altri formati di documenti online utilizzando Swift." urlsection="conversion/gif-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti un file GIF in PPTX in Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da GIF a PPTX è un compito complesso. Tutte le transizioni dal formato GIF al formato PPTX vengono eseguite dal nostro SDK Swift mantenendo il contenuto strutturale e logico principale del foglio di calcolo GIF di origine. La nostra libreria Swift è una soluzione professionale per convertire file GIF in PPTX online. Questo Cloud SDK offre agli sviluppatori Swift funzionalità potenti e output PPTX perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Swift utilizzando REST API per convertire GIF in formato PPTX" gistPath="" %}}
 
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
    let workbook:String = "Book1.gif"
    let format:String? = "pptx"     
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
            let fileName = "dest.pptx"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Swift API per convertire GIF in PPTX" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo celluleWorkbookPutConvertWorkbook per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>macOS Monterey 12.4</li>
<li>Veloce 4.2</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
