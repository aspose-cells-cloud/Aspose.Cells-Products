﻿---
title:  SXC a XLSX Convertir API para C#
description:  Usando Aspose.Cells Cloud SDK para C# para convertir un archivo de formato SXC a un archivo de formato XLSX.
url: /es/net/conversion/sxc-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API para convertir SXC a XLSX" h2="C# biblioteca para convertir SXC a XLSX" p="Use Cells Conversion REST API para crear flujos de trabajo de hojas de cálculo personalizados en Net. Esta es una solución profesional para convertir SXC a XLSX y otros formatos de documentos en línea usando C#." urlsection="conversion/sxc-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta un archivo SXC a XLSX en C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de SXC a XLSX es una tarea compleja. Todas las transiciones de formato SXC a XLSX se realizan mediante nuestro SDK C# mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo SXC de origen. Nuestra biblioteca C# es una solución profesional para convertir archivos SXC a XLSX en línea. Este SDK de la nube ofrece a los desarrolladores de C# una potente funcionalidad y una salida XLSX perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en C# usando REST API para convertir SXC a formato XLSX" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.sxc";
    string format = "xlsx";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xlsx";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar C# API para convertir SXC a XLSX" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método CellsWorkbookPutConvertWorkbook para obtener el flujo resultante</li>
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