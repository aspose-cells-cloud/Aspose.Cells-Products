﻿---
title:  Salva XLTX come SXC API per Swift
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/swift/saveas/xltx-to-sxc/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API per salvare XLTX come SXC" h2="Libreria Swift per salvare XLTX come SXC" p="Utilizza Cells SaveAs REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Swift. Questa è una soluzione professionale per salvare XLTX come SXC e altri formati di documenti online utilizzando Swift." urlsection="saveas/xltx-to-sxc/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file XLTX come SXC in Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da XLTX come SXC è un compito complesso. Tutte le transizioni di formato da XLTX a SXC vengono eseguite dal nostro Swift SDK mantenendo il principale contenuto strutturale e logico del foglio di calcolo XLTX di origine. La nostra libreria Swift è una soluzione professionale per salvare XLTX come file SXC online. Questo Cloud SDK offre agli sviluppatori Swift potenti funzionalità e un output SXC perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Swift utilizzando REST API per salvare XLTX come formato SXC" gistPath="" %}}
  
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
            return
        }
        expectation1.fulfill()
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)     
    let expectation = self.expectation(description: "saveAs")
    let name:String = BOOK1.xltx
    let saveOptions:PdfSaveOptions? = PdfSaveOptions(enableHTTPCompression: nil, saveFormat: "pdf", clearData: nil, cachedFileFolder: nil, validateMergedAreas: nil, refreshChartCache: nil, createDirectory: nil, sortNames: nil, calculateFormula: nil, checkFontCompatibility: nil, onePagePerSheet: true, compliance: nil, defaultFont: nil, printingPageType: nil, imageType: nil, desiredPPI: nil, jpegQuality: nil, securityOptions: nil)
    let newfilename:String = "newbook.sxc"
    let isAutoFitRows:Bool? = true
    let isAutoFitColumns:Bool? = true
    let folder:String = TEMPFOLDER
    let storageName:String? = nil        
    CellsAPI.cellsSaveAsPostDocumentSaveAs(name: name, saveOptions: saveOptions, newfilename: newfilename, isAutoFitRows: isAutoFitRows, isAutoFitColumns: isAutoFitColumns, folder: folder, storageName: storageName)
    {
        (response, error) in
        guard error == nil else {
            return
        }            
        if let response = response {
            expectation.fulfill()
        }
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Swift API per salvare XLTX come SXC" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo cellsSaveAsPostDocumentSaveAs per ottenere il flusso risultante</li>
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