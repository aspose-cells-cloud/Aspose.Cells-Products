﻿---
title:  Guarde ODS como XLTX API para Swift
description:  Uso de Aspose.Cells Cloud SDK para Swift para guardar el archivo en formato ODS como archivo en formato XLTX.
url: /es/swift/saveas/ods-to-xltx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API para guardar ODS como XLTX" h2="Biblioteca Swift para guardar ODS como XLTX" p="Utilice Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Swift. Esta es una solución profesional para guardar ODS como XLTX y otros formatos de documentos en línea usando Swift." urlsection="saveas/ods-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo ODS como XLTX en Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de ODS como XLTX es una tarea compleja. Todas las transiciones de formato ODS a XLTX las realiza nuestro Swift SDK mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo ODS de origen. Nuestra biblioteca Swift es una solución profesional para guardar ODS como archivos XLTX en línea. Este Cloud SDK ofrece a los desarrolladores de Swift una potente funcionalidad y una salida XLTX perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Swift usando REST API para guardar ODS en formato XLTX" gistPath="" %}}
  
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
    let name:String = BOOK1.ods
    let saveOptions:PdfSaveOptions? = PdfSaveOptions(enableHTTPCompression: nil, saveFormat: "pdf", clearData: nil, cachedFileFolder: nil, validateMergedAreas: nil, refreshChartCache: nil, createDirectory: nil, sortNames: nil, calculateFormula: nil, checkFontCompatibility: nil, onePagePerSheet: true, compliance: nil, defaultFont: nil, printingPageType: nil, imageType: nil, desiredPPI: nil, jpegQuality: nil, securityOptions: nil)
    let newfilename:String = "newbook.xltx"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Swift API para guardar ODS como XLTX" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método cellSaveAsPostDocumentSaveAs para obtener la secuencia resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>macOS Monterey 12.4</li>
<li>Rápido 4.2</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
