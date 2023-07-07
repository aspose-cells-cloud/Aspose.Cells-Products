---
title: Esporta IMMAGINE in PNG dal foglio di calcolo utilizzando Swift API
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
url: /it/swift/export/picture-to-png/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API per esportare l\'IMMAGINE nel file PNG" h2="Libreria Swift per esportare IMMAGINE nel file PNG" p="Usa Cells Esporta REST API per esportare i flussi di lavoro degli oggetti interni del foglio di calcolo in Swift. Questa è una soluzione professionale per esportare l\'IMMAGINE nel file in formato PNG dal foglio di calcolo online utilizzando Swift." urlsection="export/picture-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Esporta l\'oggetto PICTURE nel file di formato PNG in Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto PICTURE nel file PNG dal foglio di calcolo è un'attività complessa. L'esportazione delle transizioni di formato da IMMAGINE a PNG viene eseguita dal nostro SDK Swift mantenendo il contenuto strutturale e logico principale del foglio di calcolo IMMAGINE di origine. La nostra libreria Swift è una soluzione professionale per esportare oggetti PICTURE in file in formato PNG online. Questo Cloud SDK offre agli sviluppatori Swift potenti funzionalità e un output PNG perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Swift utilizzando REST API per esportare IMMAGINE nel formato PNG dal foglio di calcolo" gistPath="" %}}
  
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
    let objectType:String = "picture"
    let format:String = "png"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Swift API per esportare IMMAGINE in PNG" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo postExport per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
