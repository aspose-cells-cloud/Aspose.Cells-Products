﻿---
title:  Guardar JPG como XLSX API para Go
description:  Usando Aspose.Cells Cloud SDK for Go para guardar el archivo de formato JPG como archivo de formato XLSX.
url: /es/go/saveas/jpg-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Vaya al API para guardar JPG como XLSX" h2="Ir a la biblioteca para guardar JPG como XLSX" p="Utilice Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Go. Esta es una solución profesional para guardar JPG como XLSX y otros formatos de documentos en línea usando Go." urlsection="saveas/jpg-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guardar un archivo JPG como XLSX en Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de JPG como XLSX es una tarea compleja. Todas las transiciones de formato JPG a XLSX se realizan mediante nuestro Go SDK mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo JPG de origen. Nuestra biblioteca Go es una solución profesional para guardar archivos JPG como XLSX en línea. Este SDK de Cloud ofrece a los desarrolladores de Go una potente funcionalidad y una salida XLSX perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Go usando REST API para guardar JPG como formato XLSX" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.jpg"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xlsx"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Go API para guardar JPG como XLSX" >}}
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