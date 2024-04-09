---
title:  Guarde HTML como PNG usando Go
description:  Utilizando Aspose.Cells Cloud SDK para Go para guardar el archivo de formato HTML como archivo de formato PNG.
kwords: Excel, Save HTML as PNG, REST, Go
howto: How to save HTML as PNG using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar HTML como PNG" h2="Vaya a la biblioteca para guardar HTML como PNG" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Go. Esta es una solución profesional para guardar HTML como PNG y otros formatos de documentos en línea usando Go." urlsection="saveas/html-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo HTML como PNG en Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de HTML como PNG es una tarea compleja. Nuestro Go SDK realiza todas las transiciones de formato HTML a PNG mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo de origen HTML. Nuestra biblioteca Go es una solución profesional para guardar archivos HTML como PNG en línea. Este SDK de nube ofrece a los desarrolladores de Go una potente funcionalidad y un resultado PNG perfecto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código Go para guardar HTML como PNG usando REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.html"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.png"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo guardar HTML como PNG usando la biblioteca Cells Cloud Go." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Go y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en go.</li>
<li>Utilice el método `PostWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>vaya a la versión go1.13.0 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
