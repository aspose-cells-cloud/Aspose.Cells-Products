---
title:  Guarde CSV como TXT usando Java
description: Utilizando Aspose.Cells Cloud SDK for Java para guardar el archivo en formato CSV como archivo en formato TXT.
kwords: Excel, Save CSV as TXT, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save CSV as TXT using the Cells Cloud Java library.","description": "How to save CSV as TXT using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/csv-to-txt/","step": [{ "@type": "HowToStep","name": "How to save CSV as TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/csv-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save CSV as TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/csv-to-txt/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save CSV as TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/csv-to-txt/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save CSV as TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/csv-to-txt/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar CSV como TXT" h2="Biblioteca Java para guardar CSV como TXT" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Java. Esta es una solución profesional para guardar CSV como TXT y otros formatos de documentos en línea usando Java." urlsection="saveas/csv-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo CSV como TXT en Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de CSV como TXT es una tarea compleja. Todas las transiciones de formato CSV a TXT se realizan mediante nuestro SDK Java mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo CSV de origen. Nuestra biblioteca Java es una solución profesional para guardar CSV como archivos TXT en línea. Este Cloud SDK ofrece a los desarrolladores de Java una potente funcionalidad y una salida TXT perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Ejemplo de código para guardar CSV como TXT usando REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.csv";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.txt";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo guardar CSV como TXT usando la biblioteca Cells Cloud Java." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Java y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Java.</li>
<li>Utilice el método `postWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE entorno de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
