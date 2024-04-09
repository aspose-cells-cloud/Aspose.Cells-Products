---
title:  Guarde PNG como TIFF usando Go
description:  Utilizando Aspose.Cells Cloud SDK para Go para guardar el archivo de formato PNG como archivo de formato TIFF.
kwords: Excel, Save PNG as TIFF, REST, Go
howto: How to save PNG as TIFF using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar PNG como TIFF" h2="Vaya a la biblioteca para guardar PNG como TIFF" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Go. Esta es una solución profesional para guardar PNG como TIFF y otros formatos de documentos en línea usando Go." urlsection="saveas/png-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo PNG como TIFF en Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de PNG como TIFF es una tarea compleja. Nuestro Go SDK realiza todas las transiciones de formato PNG a TIFF mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo de origen PNG. Nuestra biblioteca Go es una solución profesional para guardar archivos PNG como TIFF en línea. Este SDK de nube ofrece a los desarrolladores de Go una potente funcionalidad y un resultado TIFF perfecto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código Go para guardar PNG como TIFF usando REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.png"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.tiff"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo guardar PNG como TIFF usando la biblioteca Cells Cloud Go." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Go y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en go.</li>
<li>Utilice el método `PostWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>vaya a la versión go1.13.0 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
