---
title:  Convierta TXT a XLTX usando Go
description: Utilizar el SDK de nube Aspose.Cells para Go para convertir un archivo de formato TXT a un archivo de formato XLTX.
kwords: Excel, Convert TXT to XLTX, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert TXT to XLTX using the Cells Cloud Go library.","description": "How to convert TXT to XLTX using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/conversion/txt-to-xltx/","step": [{ "@type": "HowToStep","name": "How to convert TXT to XLTX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-xltx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert TXT to XLTX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-xltx/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert TXT to XLTX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-xltx/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to convert TXT to XLTX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-xltx/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir TXT a XLTX" h2="Ir a la biblioteca para convertir TXT a XLTX" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos de Go. Esta es una solución profesional para convertir TXT a XLTX y otros formatos de documentos en línea usando Go." urlsection="conversion/txt-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta TXT a XLTX usando Cells Cloud SDK para Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de TXT a XLTX puede ser una tarea compleja. Nuestro Go SDK maneja todas las conversiones de formato TXT a XLTX mientras preserva el contenido estructural y lógico principal de la hoja de cálculo TXT de origen. Nuestra biblioteca Go proporciona una solución profesional para convertir archivos TXT a XLTX en línea. Este Cloud SDK brinda a los desarrolladores de Go una potente funcionalidad y garantiza una salida XLTX de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Vaya ejemplo de código para convertir TXT a XLTX usando Cells Cloud SDK" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.txt")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "xltx"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.xltx")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo convertir TXT a XLTX usando la biblioteca Cells Cloud Go." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Go y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en go.</li>
<li>Utilice el método `PutConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>vaya a la versión go1.13.0 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
