---
title:  Guarde XLSX como XLTX usando C#
description: Utilizando Aspose.Cells Cloud SDK para C# para guardar el archivo en formato XLSX como archivo en formato XLTX.
kwords: Excel, Save XLSX as XLTX, REST, C#
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSX as XLTX using the Cells Cloud Net library.","description": "How to save XLSX as XLTX using the Cells Cloud Net library.","image": {"@type": "ImageObject"},"url": "/net/saveas/xlsx-to-xltx/","step": [{ "@type": "HowToStep","name": "How to save XLSX as XLTX using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xlsx-to-xltx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSX as XLTX using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xlsx-to-xltx/","text": "Install C# library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSX as XLTX using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xlsx-to-xltx/","text": "Open the source file in C#",},{ "@type": "HowToStep","name": "How to save XLSX as XLTX using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xlsx-to-xltx/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar XLSX como XLTX" h2="Biblioteca C# para guardar XLSX como XLTX" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Net. Esta es una solución profesional para guardar XLSX como XLTX y otros formatos de documentos en línea usando C#." urlsection="saveas/xlsx-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo XLSX como XLTX en C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLSX como XLTX es una tarea compleja. Todas las transiciones de formato XLSX a XLTX se realizan mediante nuestro SDK C# mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLSX de origen. Nuestra biblioteca C# es una solución profesional para guardar XLSX como archivos XLTX en línea. Este SDK de nube ofrece a los desarrolladores de C# una potente funcionalidad y una salida XLTX perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Ejemplo de código para guardar XLSX como XLTX usando REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsx";
    string newfilename = "Book1SaveAs.xltx";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo guardar XLSX como XLTX usando la biblioteca Cloud Net Cells." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca C# y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en C#</li>
<li>Utilice el método `PostWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>NET Framework 4.5.2 o más reciente</li>
<li>Net Standard 2.0 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
