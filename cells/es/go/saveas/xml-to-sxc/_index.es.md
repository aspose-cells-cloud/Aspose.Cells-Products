﻿---
title:  Guardar XML como SXC API para Go
description:  Usando Aspose.Cells Cloud SDK for Go para guardar el archivo de formato XML como archivo de formato SXC.
url: /es/go/saveas/xml-to-sxc/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Vaya a API para guardar XML como SXC" h2="Ir a la biblioteca para guardar XML como SXC" p="Utilice Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Go. Esta es una solución profesional para guardar XML como SXC y otros formatos de documentos en línea usando Go." urlsection="saveas/xml-to-sxc/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guardar un archivo XML como SXC en Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XML como SXC es una tarea compleja. Todas las transiciones de formato XML a SXC las realiza nuestro Go SDK mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XML de origen. Nuestra biblioteca Go es una solución profesional para guardar XML como archivos SXC en línea. Este SDK de Cloud ofrece a los desarrolladores de Go una potente funcionalidad y un resultado SXC perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Go usando REST API para guardar XML como formato SXC" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.xml"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.sxc"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Go API para guardar XML como SXC" >}}
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