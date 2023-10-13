﻿---
title:  Guardar GIF como XLS API para Go
description:  Usando Aspose.Cells Cloud SDK for Go para guardar el archivo de formato GIF como archivo de formato XLS.
url: /es/go/saveas/gif-to-xls/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Vaya al API para guardar GIF como XLS" h2="Ir a la biblioteca para guardar GIF como XLS" p="Utilice Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Go. Esta es una solución profesional para guardar GIF como XLS y otros formatos de documentos en línea usando Go." urlsection="saveas/gif-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guardar un archivo GIF como XLS en Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de GIF como XLS es una tarea compleja. Todas las transiciones de formato GIF a XLS se realizan mediante nuestro Go SDK mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo GIF de origen. Nuestra biblioteca Go es una solución profesional para guardar GIF como archivos XLS en línea. Este SDK de Cloud brinda a los desarrolladores de Go una funcionalidad poderosa y una salida XLS perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Go usando REST API para guardar GIF como formato XLS" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.gif"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xls"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Go API para guardar GIF como XLS" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método CellsSaveAsPostDocumentSaveAs para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>ir a la versión go1.13.0 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}