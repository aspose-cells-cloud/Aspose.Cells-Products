---
title:  Guarde TSV como EMF usando Java
description:  Utilizando Aspose.Cells Cloud SDK for Java para guardar el archivo en formato TSV como archivo en formato EMF.
kwords: Excel, Save TSV as EMF, REST, Java
howto: How to save TSV as EMF using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar TSV como EMF" h2="Biblioteca Java para guardar TSV como EMF" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Java. Esta es una solución profesional para guardar TSV como EMF y otros formatos de documentos en línea usando Java." urlsection="saveas/tsv-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo TSV como EMF en Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de TSV como EMF es una tarea compleja. Todas las transiciones de formato TSV a EMF las realiza nuestro SDK Java mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo TSV de origen. Nuestra biblioteca Java es una solución profesional para guardar TSV como archivos EMF en línea. Este SDK de nube ofrece a los desarrolladores de Java una funcionalidad potente y un resultado de EMF perfecto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Ejemplo de código para guardar TSV como EMF usando REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.tsv";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.emf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo guardar TSV como EMF usando la biblioteca Cells Cloud Java." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Java y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Java.</li>
<li>Utilice el método `postWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE entorno de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
