---
title: Exportar IMAGEN a SVG desde hoja de cálculo usando Swift API
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} mediante {2}.
url: /es/swift/export/picture-to-svg/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API para exportar la IMAGEN al archivo SVG" h2="Biblioteca Swift para exportar IMAGEN al archivo SVG" p="Use Cells Exportar REST API para exportar flujos de trabajo de objetos internos de hojas de cálculo en Swift. Esta es una solución profesional para exportar IMAGEN a un archivo de formato SVG desde una hoja de cálculo en línea usando Swift." urlsection="export/picture-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportar objeto IMAGEN al archivo de formato SVG en Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar el objeto IMAGEN al archivo SVG desde la hoja de cálculo es una tarea compleja. Nuestro Swift SDK realiza las transiciones de formato de exportación de IMAGEN a SVG mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo de IMAGEN de origen. Nuestra biblioteca Swift es una solución profesional para exportar objetos de IMAGEN a archivos de formato SVG en línea. Este SDK de Cloud brinda a los desarrolladores de Swift una funcionalidad poderosa y un resultado SVG perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Swift usando REST API para exportar IMAGEN al formato SVG desde la hoja de cálculo" gistPath="" %}}
  
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Swift API para exportar IMAGEN a SVG" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método postExport para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
