---
title:  Guarde XLT como XLS usando Java
description:  Utilizando Aspose.Cells Cloud SDK for Java para guardar el archivo en formato XLT como archivo en formato XLS.
kwords: Excel, Save XLT as XLS, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLT as XLS using the Cells Cloud Java library.","description": "How to save XLT as XLS using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/xlt-to-xls/","step": [{ "@type": "HowToStep","name": "How to save XLT as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xlt-to-xls/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLT as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xlt-to-xls/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLT as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xlt-to-xls/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save XLT as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xlt-to-xls/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar XLT como XLS" h2="Biblioteca Java para guardar XLT como XLS" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Java. Esta es una solución profesional para guardar XLT como XLS y otros formatos de documentos en línea usando Java." urlsection="saveas/xlt-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo XLT como XLS en Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLT como XLS es una tarea compleja. Todas las transiciones de formato XLT a XLS se realizan mediante nuestro SDK Java mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLT de origen. Nuestra biblioteca Java es una solución profesional para guardar XLT como archivos XLS en línea. Este SDK de nube ofrece a los desarrolladores de Java una funcionalidad potente y una salida XLS perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Ejemplo de código para guardar XLT como XLS usando REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xlt";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xls";
    String folder ="CellsTests";
    try 
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo guardar XLT como XLS usando la biblioteca Cells Cloud Java." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Java y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Java.</li>
<li>Utilice el método `postWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE entorno de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
