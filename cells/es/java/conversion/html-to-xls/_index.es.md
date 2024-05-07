---
title:  Convierta HTML a XLS usando Java
description:  Utilizando el Aspose.Cells Cloud SDK for Java para convertir un archivo de formato HTML a un archivo de formato XLS.
kwords: Excel, Convert HTML to XLS, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert HTML to XLS using the Cells Cloud Java library.","description": "How to convert HTML to XLS using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/conversion/html-to-xls/","step": [{ "@type": "HowToStep","name": "How to convert HTML to XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-xls/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert HTML to XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-xls/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert HTML to XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-xls/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to convert HTML to XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-xls/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir HTML a XLS" h2="Biblioteca Java para convertir HTML a XLS" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Java proyectos. Esta es una solución profesional para convertir HTML a XLS y otros formatos de documentos en línea usando Java." urlsection="conversion/html-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta HTML a XLS usando Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de HTML a XLS puede ser una tarea compleja. Nuestro SDK Java maneja todas las conversiones de formato HTML a XLS al tiempo que conserva el contenido estructural y lógico principal de la hoja de cálculo de origen HTML. Nuestra biblioteca Java proporciona una solución profesional para convertir archivos HTML a XLS en línea. Este SDK de nube brinda a los desarrolladores Java una potente funcionalidad y garantiza una salida XLS de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Ejemplo de código para convertir HTML a XLS usando Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.html";
            String format = "xls";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xls";
            try {
                CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
                File response = cellsApi.cellsWorkbookPutConvertWorkbook(new File(name), format, password, outPath, null,null);            
                if(response.canRead())
                {
                    if(response.exists()){
                        response.renameTo(new File(destFile));
                    }                
                }
            }
            catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo convertir HTML a XLS usando la biblioteca Cells Cloud Java." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Java y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Java.</li>
<li>Utilice el método `putConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE entorno de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
