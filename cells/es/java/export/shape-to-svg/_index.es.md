---
title:  Exporte SHAPE a SVG desde Excel usando Cells Cloud SDK for Java
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} usando {2}.
kwords: Excel, shape, svg, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to SVG","description": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to SVG","image": {"@type": "ImageObject"},"url": "/java/export/shape-to-svg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/java/export/shape-to-svg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/java/export/shape-to-svg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/java/export/shape-to-svg/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportar FORMA a SVG desde Excel" h2="Biblioteca Java para exportar SHAPE al archivo SVG" p="Utilice Exportar API de Cells Cloud para exportar flujos de trabajo de objetos internos de archivos Excel en Java. Esta es una solución profesional para exportar FORMA a un archivo de formato SVG desde una hoja de cálculo en línea usando Java." urlsection="export/shape-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporte el objeto SHAPE al archivo de formato SVG usando Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar el objeto SHAPE al archivo SVG desde el archivo Excel es una tarea compleja. Nuestro SDK Java realiza la exportación de transiciones de formato SHAPE a SVG manteniendo el contenido estructural y lógico principal de la hoja de cálculo SHAPE de origen. Nuestra biblioteca Java es una solución profesional para exportar objetos SHAPE a archivos de formato SVG en línea. Este SDK de nube ofrece a los desarrolladores de Java una funcionalidad potente y un resultado de SVG perfecto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código en Java usando REST API para exportar FORMA al formato SVG desde una hoja de cálculo" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.*;
    import java.util.HashMap;
    import java.util.List;
    import java.util.Base64;
    import com.aspose.cloud.cells.api.*;
    import com.aspose.cloud.cells.model.*;
    public class Export {
        public static void main(String[] args) {
            String format = "svg";
            String objectType = "shape";
            HashMap<String,File> fileMap = new HashMap<String,File>();
            fileMap.put("Book1.xlsx" ,new File("C:\Book1.xlsx") );
            fileMap.put("myDocument.xlsx" ,new File("C:\myDocument.xlsx") );
            try {
                LightCellsApi cellsApi = new LightCellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"),"v3.0","https://api.aspose.cloud");
                FilesResult response = cellsApi.postExport(fileMap,objectType, format,null);            
                List<FileInfo> files = response.getFiles();
                String filename = files.get(0).getFilename();
                String fileContent = files.get(0).getFileContent();
                byte[] data = Base64.getDecoder().decode(fileContent);
                OutputStream outputStream = new FileOutputStream(filename);
                outputStream.write(data,0,data.length);
                outputStream.close();
            }catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK for Java para exportar objetos de Excel SHAPE a SVG" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `postExport` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE entorno de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
