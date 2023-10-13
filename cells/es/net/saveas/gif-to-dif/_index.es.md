﻿---
title:  Guardar GIF como DIF API para C#
description:  Usando Aspose.Cells Cloud SDK para C# para guardar el archivo de formato GIF como archivo de formato DIF.
url: /es/net/saveas/gif-to-dif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API para guardar GIF como DIF" h2="C# biblioteca para guardar GIF como DIF" p="Use Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Net. Esta es una solución profesional para guardar GIF como DIF y otros formatos de documentos en línea usando C#." urlsection="saveas/gif-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guardar un archivo GIF como DIF en C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de GIF como DIF es una tarea compleja. Todas las transiciones de formato GIF a DIF se realizan mediante nuestro SDK C# mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo GIF de origen. Nuestra biblioteca C# es una solución profesional para guardar GIF como archivos DIF en línea. Este SDK de Cloud ofrece a los desarrolladores de C# una potente funcionalidad y una salida DIF perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en C# usando REST API para guardar GIF como formato DIF" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.gif";
    string newfilename = "Book1SaveAs.dif";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar C# API para guardar GIF como DIF" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método CellsSaveAsPostDocumentSaveAs para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>NET Framework 4.5.2 o más reciente</li>
<li>Net Standard 2.0 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}