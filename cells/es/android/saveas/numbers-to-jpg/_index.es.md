﻿---
title:  Guardar NÚMEROS como JPG API para Android
description:  Usando Aspose.Cells Cloud SDK para Android para guardar el archivo de formato NUMBERS como archivo de formato JPG.
url: /es/android/saveas/numbers-to-jpg/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API para guardar NÚMEROS como JPG" h2="Biblioteca de Android para guardar NÚMEROS como JPG" p="Use Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Android. Esta es una solución profesional para guardar NÚMEROS como JPG y otros formatos de documentos en línea usando Android." urlsection="saveas/numbers-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo NUMBERS como JPG en Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de NUMBERS como JPG es una tarea compleja. Nuestro SDK de Android realiza todas las transiciones de formato NUMBERS a JPG mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo NUMBERS de origen. Nuestra biblioteca de Android es una solución profesional para guardar NÚMEROS como archivos JPG en línea. Este SDK de la nube brinda a los desarrolladores de Android una funcionalidad poderosa y una salida JPG perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Android usando REST API para guardar NÚMEROS como formato JPG" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.numbers";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.jpg";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Java API para guardar NÚMEROS como JPG" >}}
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