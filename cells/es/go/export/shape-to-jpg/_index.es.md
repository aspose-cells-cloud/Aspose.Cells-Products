---
title: Exporte SHAPE a JPG desde Excel usando Cells Cloud SDK for Go
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} usando {2}.
kwords: Excel, shape, jpg, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Go to export objects from Excel SHAPE to JPG","description": "How to use Cells Cloud SDK for Go to export objects from Excel SHAPE to JPG","image": {"@type": "ImageObject"},"url": "/go/export/shape-to-jpg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel SHAPE to JPG step 1", "image": {"@type": "ImageObject",},"url": "/go/export/shape-to-jpg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel SHAPE to JPG step 1", "image": {"@type": "ImageObject",},"url": "/go/export/shape-to-jpg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel SHAPE to JPG step 1", "image": {"@type": "ImageObject",},"url": "/go/export/shape-to-jpg/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportar FORMA a JPG desde Excel" h2="Ir a la biblioteca para exportar SHAPE a un archivo JPG" p="Utilice Exportar API de Cells Cloud para exportar flujos de trabajo de objetos internos de archivos Excel en Go. Esta es una solución profesional para exportar archivos SHAPE a formato JPG desde una hoja de cálculo en línea usando Go." urlsection="export/shape-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporte el objeto SHAPE a un archivo en formato JPG usando Cells Cloud SDK for Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar un objeto SHAPE a un archivo JPG desde el archivo Excel es una tarea compleja. Nuestro Go SDK realiza la exportación de transiciones de formato SHAPE a JPG mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo SHAPE de origen. Nuestra biblioteca Go es una solución profesional para exportar objetos SHAPE a archivos en formato JPG en línea. Este Cloud SDK ofrece a los desarrolladores de Go una funcionalidad potente y una salida JPG perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código en Go usando REST API para exportar SHAPE a formato JPG desde una hoja de cálculo" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "encoding/base64"
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewLightCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    var files map[string]string
	    files = make(map[string]string)
	    files["Book1.xlsx"] = "C:/Book1.xlsx"
	    files["myDocument.xlsx"] = "C:/myDocument.xlsx"
	    postExportOpts := new(asposecellscloud.PostExportOpts)
	    postExportOpts.ObjectType = "shape"
	    postExportOpts.Format = "jpg"
	    filesresult, _, err := instance.PostExport(files, postExportOpts)
	    if err != nil {
		    return
	    }
	    print(filesresult.Files[0].Filename)
	    originalStringBytes, err1 := base64.StdEncoding.DecodeString(filesresult.Files[0].FileContent)
	    if err1 != nil {
		    return
	    }
	    f, err2 := os.Create(filesresult.Files[0].Filename)
	    if err2 != nil {
		    return
	    }
	    _, err3 := f.Write(originalStringBytes)
	    if err3 != nil {
		    return
	    }
	    f.Close()
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Go para exportar objetos de Excel SHAPE a JPG" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `postExport` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>vaya a la versión go1.13.0 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
