﻿---
title:  Guardar XLSX como XPS API for Java
description:  Usando Aspose.Cells Cloud SDK for Java para guardar el archivo de formato XLSX como archivo de formato XPS.
url: /es/java/saveas/xlsx-to-xps/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API para guardar XLSX como XPS" h2="Biblioteca Java para guardar XLSX como XPS" p="Use Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Java. Esta es una solución profesional para guardar XLSX como XPS y otros formatos de documentos en línea usando Java." urlsection="saveas/xlsx-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo XLSX como XPS en Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLSX como XPS es una tarea compleja. Todas las transiciones de formato XLSX a XPS se realizan mediante nuestro SDK Java mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLSX de origen. Nuestra biblioteca Java es una solución profesional para guardar archivos XLSX como XPS en línea. Este SDK de Cloud ofrece a los desarrolladores de Java una potente funcionalidad y un resultado XPS perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Java usando REST API para guardar XLSX como formato XPS" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xlsx";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xps";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Java API para guardar XLSX como XPS" >}}
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