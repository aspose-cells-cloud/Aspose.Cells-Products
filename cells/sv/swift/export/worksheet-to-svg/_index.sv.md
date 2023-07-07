---
title:  Exportera ARBETSBLAD till SVG från kalkylblad med Swift API
description:  Aspose.Cells Cloud REST API stöder export av filer från {0} till {1}-format med {2}.
url: /sv/swift/export/worksheet-to-svg/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API för att exportera ARBETSBLAD till SVG fil" h2="Swift-bibliotek för att exportera ARBETSBLAD till SVG-fil" p="Använd Cells Export REST API för att exportera arbetsflöden för interna objekt i kalkylark i Swift. Detta är en professionell lösning för att exportera ARBETSBLAD till SVG filformat från kalkylblad online med Swift." urlsection="export/worksheet-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportera WORKSHEET-objekt till filformatet SVG i Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportera WORKSHEET-objekt till SVG-fil från kalkylblad är en komplex uppgift. Exportera WORKSHEET till SVG formatövergångar utförs av vår Swift SDK samtidigt som källarbetsbladets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Swift-bibliotek är en professionell lösning för att exportera WORKSHEET-objekt till filer i SVG-format online. Denna Cloud SDK ger Swift-utvecklare kraftfull funktionalitet och perfekt SVG-utgång.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Swift med REST API för att exportera WORKSHEET till SVG-format från kalkylark" gistPath="" %}}
  
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
    let objectType:String = "worksheet"
    let format:String = "svg"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Swift API för att exportera ARBETSBLAD till SVG" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop postExport-metoden för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
