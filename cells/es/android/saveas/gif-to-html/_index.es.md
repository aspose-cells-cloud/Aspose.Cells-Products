﻿---
title:  Guardar GIF como HTML API para Android
description: Usando Aspose.Cells Cloud SDK para Android para guardar el archivo de formato GIF como archivo de formato HTML.
url: /es/android/saveas/gif-to-html/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API para guardar GIF como HTML" h2="Biblioteca de Android para guardar GIF como HTML" p="Use Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Android. Esta es una solución profesional para guardar GIF como HTML y otros formatos de documentos en línea usando Android." urlsection="saveas/gif-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo GIF como HTML en Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo desde GIF como HTML es una tarea compleja. Nuestro SDK de Android realiza todas las transiciones de formato GIF a HTML mientras mantiene el contenido estructural y lógico principal de la hoja de cálculo GIF de origen. Nuestra biblioteca de Android es una solución profesional para guardar GIF como archivos HTML en línea. Este SDK de la nube brinda a los desarrolladores de Android una funcionalidad poderosa y una salida HTML perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Android usando REST API para guardar GIF como formato HTML" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.gif";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Java API para guardar GIF como HTML" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método cellSaveAsPostDocumentSaveAs para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Android 7 o más reciente</li>
<li>Java(TM) SE Entorno de tiempo de ejecución</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}