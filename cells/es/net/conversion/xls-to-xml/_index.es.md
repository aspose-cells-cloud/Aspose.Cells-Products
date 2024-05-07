---
title:  Convierta XLS a XML usando C#
description:  Utilizar el SDK de la nube Aspose.Cells para C# para convertir un archivo de formato XLS a un archivo de formato XML.
kwords: Excel, Convert XLS to XML, REST, C#
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLS to XML using the Cells Cloud Net library.","description": "How to convert XLS to XML using the Cells Cloud Net library.","image": {"@type": "ImageObject"},"url": "/net/conversion/xls-to-xml/","step": [{ "@type": "HowToStep","name": "How to convert XLS to XML using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/xls-to-xml/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLS to XML using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/xls-to-xml/","text": "Install C# library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLS to XML using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/xls-to-xml/","text": "Open the source file in C#",},{ "@type": "HowToStep","name": "How to convert XLS to XML using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/xls-to-xml/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider "},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir XLS a XML" h2="Biblioteca C# para convertir XLS a XML" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos de Net. Esta es una solución profesional para convertir XLS a XML y otros formatos de documentos en línea usando C#." urlsection="conversion/xls-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta XLS a XML usando Cells Cloud SDK para C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de XLS a XML puede ser una tarea compleja. Nuestro SDK C# maneja todas las conversiones de formato XLS a XML y al mismo tiempo conserva el contenido estructural y lógico principal de la hoja de cálculo XLS de origen. Nuestra biblioteca C# proporciona una solución profesional para convertir archivos XLS a XML en línea. Este SDK de nube brinda a los desarrolladores C# una potente funcionalidad y garantiza una salida XML de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Ejemplo de código para convertir XLS a XML usando Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xls";
    string format = "xml";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xml";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo convertir XLS a XML usando la biblioteca Cloud Net Cells." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca C# y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en C#</li>
<li>Utilice el método `PutConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>NET Framework 4.5.2 o más reciente</li>
<li>Net Standard 2.0 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
