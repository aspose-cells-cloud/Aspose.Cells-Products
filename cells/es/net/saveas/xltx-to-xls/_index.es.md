---
title:  Guarde XLTX como XLS usando C#
description:  Utilizando Aspose.Cells Cloud SDK para C# para guardar el archivo en formato XLTX como archivo en formato XLS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Guardar XLTX como XLS" h2="Biblioteca C# para guardar XLTX como XLS" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Net. Esta es una solución profesional para guardar XLTX como XLS y otros formatos de documentos en línea usando C#." urlsection="saveas/xltx-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo XLTX como XLS en C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLTX como XLS es una tarea compleja. Todas las transiciones de formato XLTX a XLS se realizan mediante nuestro SDK C# manteniendo el contenido estructural y lógico principal de la hoja de cálculo XLTX de origen. Nuestra biblioteca C# es una solución profesional para guardar XLTX como archivos XLS en línea. Este SDK de nube ofrece a los desarrolladores de C# una funcionalidad potente y una salida XLS perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Ejemplo de código para guardar XLTX como XLS usando REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xltx";
    string newfilename = "Book1SaveAs.xls";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK for Net para guardar archivos Excel en otros formatos XLTX como XLS" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `PostWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>NET Framework 4.5.2 o más reciente</li>
<li>Net Standard 2.0 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
