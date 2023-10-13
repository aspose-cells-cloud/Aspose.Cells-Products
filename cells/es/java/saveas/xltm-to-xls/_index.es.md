﻿---
title:  Guardar XLTM como XLS API for Java
description:  Usando Aspose.Cells Cloud SDK for Java para guardar el archivo de formato XLTM como archivo de formato XLS.
url: /es/java/saveas/xltm-to-xls/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API para guardar XLTM como XLS" h2="Java biblioteca para guardar XLTM como XLS" p="Use Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Java. Esta es una solución profesional para guardar XLTM como XLS y otros formatos de documentos en línea usando Java." urlsection="saveas/xltm-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo XLTM como XLS en Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLTM como XLS es una tarea compleja. Todas las transiciones de formato XLTM a XLS se realizan mediante nuestro SDK Java mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLTM de origen. Nuestra biblioteca Java es una solución profesional para guardar XLTM como archivos XLS en línea. Este SDK de Cloud ofrece a los desarrolladores de Java una potente funcionalidad y una salida XLS perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Java usando REST API para guardar XLTM como formato XLS" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xltm";
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
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Java API para guardar XLTM como XLS" >}}
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