﻿---
title: Guarde XLSM como SXC API para C#
description:  Usando Aspose.Cells Cloud SDK para C# para guardar el archivo de formato XLSM como archivo de formato SXC.
url: /es/net/saveas/xlsm-to-sxc/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API para guardar XLSM como SXC" h2="C# biblioteca para guardar XLSM como SXC" p="Use Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Net. Esta es una solución profesional para guardar XLSM como SXC y otros formatos de documentos en línea usando C#." urlsection="saveas/xlsm-to-sxc/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo XLSM como SXC en C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLSM como SXC es una tarea compleja. Todas las transiciones de formato XLSM a SXC se realizan mediante nuestro SDK C# mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLSM de origen. Nuestra biblioteca C# es una solución profesional para guardar archivos XLSM como SXC en línea. Este Cloud SDK ofrece a los desarrolladores de C# una potente funcionalidad y un resultado SXC perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en C# usando REST API para guardar XLSM como formato SXC" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsm";
    string newfilename = "Book1SaveAs.sxc";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar C# API para guardar XLSM como SXC" >}}
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