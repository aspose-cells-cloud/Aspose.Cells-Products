---
title:  Guarde XLSB como HTML usando Java
description: Utilizando Aspose.Cells Cloud SDK for Java para guardar el archivo en formato XLSB como archivo en formato HTML.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Guarde XLSB como HTML" h2="Biblioteca Java para guardar XLSB como HTML" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Java. Esta es una solución profesional para guardar XLSB como HTML y otros formatos de documentos en línea usando Java." urlsection="saveas/xlsb-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo XLSB como HTML en Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLSB como HTML es una tarea compleja. Todas las transiciones de formato XLSB a HTML las realiza nuestro SDK Java mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLSB de origen. Nuestra biblioteca Java es una solución profesional para guardar XLSB como archivos HTML en línea. Este SDK de nube ofrece a los desarrolladores de Java una funcionalidad potente y un resultado de HTML perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Ejemplo de código para guardar XLSB como HTML usando REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xlsb";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.html";
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
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK for Java para guardar archivos Excel en otros formatos XLSB como HTML" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `postWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE entorno de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
