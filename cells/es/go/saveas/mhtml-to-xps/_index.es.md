---
title:  Guarde MHTML como XPS usando Go
description:  Utilizando Aspose.Cells Cloud SDK para Go para guardar el archivo en formato MHTML como archivo en formato XPS.
kwords: Excel, Save MHTML as XPS, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save MHTML as XPS using the Cells Cloud Go library.","description": "How to save MHTML as XPS using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/mhtml-to-xps/","step": [{ "@type": "HowToStep","name": "How to save MHTML as XPS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/mhtml-to-xps/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save MHTML as XPS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/mhtml-to-xps/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save MHTML as XPS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/mhtml-to-xps/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save MHTML as XPS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/mhtml-to-xps/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Guarde MHTML como XPS" h2="Ir a la biblioteca para guardar MHTML como XPS" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Go. Esta es una solución profesional para guardar MHTML como XPS y otros formatos de documentos en línea usando Go." urlsection="saveas/mhtml-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo MHTML como XPS en Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de MHTML como XPS es una tarea compleja. Todas las transiciones de formato MHTML a XPS las realiza nuestro Go SDK mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo MHTML de origen. Nuestra biblioteca Go es una solución profesional para guardar MHTML como archivos XPS en línea. Este SDK de nube ofrece a los desarrolladores de Go una potente funcionalidad y un resultado XPS perfecto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Vaya ejemplo de código para guardar MHTML como XPS usando REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.mhtml"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xps"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo guardar MHTML como XPS usando la biblioteca Cells Cloud Go." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Go y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en go.</li>
<li>Utilice el método `PostWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>vaya a la versión go1.13.0 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
