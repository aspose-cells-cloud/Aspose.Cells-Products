﻿---
title:  Guardar EMF como ODS API for Java
description:  Usando Aspose.Cells Cloud SDK for Java para guardar el archivo de formato EMF como archivo de formato ODS.
url: /es/java/saveas/emf-to-ods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API para guardar EMF como SAO" h2="Java biblioteca para guardar EMF como ODS" p="Use Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Java. Esta es una solución profesional para guardar EMF como ODS y otros formatos de documentos en línea usando Java." urlsection="saveas/emf-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo EMF como ODS en Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo desde EMF como ODS es una tarea compleja. Todas las transiciones de formato EMF a ODS se realizan mediante nuestro SDK Java mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo fuente EMF. Nuestra biblioteca Java es una solución profesional para guardar EMF como archivos ODS en línea. Este SDK de la nube brinda a los desarrolladores de Java una funcionalidad poderosa y una salida ODS perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Java usando REST API para guardar EMF como formato ODS" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.emf";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.ods";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Java API para guardar EMF como ODS" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método cellSaveAsPostDocumentSaveAs para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Maven 2.2.0 o más reciente</li>
<li>Java(TM) SE Entorno de tiempo de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}