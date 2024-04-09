---
title:  Guarde ODS como TSV usando C#
description:  Utilizando Aspose.Cells Cloud SDK para C# para guardar el archivo en formato ODS como archivo en formato TSV.
kwords: Excel, Save ODS as TSV, REST, C#
howto: How to save ODS as TSV using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar ODS como TSV" h2="Biblioteca C# para guardar ODS como TSV" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Net. Esta es una solución profesional para guardar ODS como TSV y otros formatos de documentos en línea usando C#." urlsection="saveas/ods-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo ODS como TSV en C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de ODS como TSV es una tarea compleja. Todas las transiciones de formato ODS a TSV se realizan mediante nuestro SDK C# mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo ODS de origen. Nuestra biblioteca C# es una solución profesional para guardar ODS como archivos TSV en línea. Este SDK de nube ofrece a los desarrolladores de C# una potente funcionalidad y una salida TSV perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Ejemplo de código para guardar ODS como TSV usando REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.ods";
    string newfilename = "Book1SaveAs.tsv";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo guardar ODS como TSV usando la biblioteca Cloud Net Cells." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca C# y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en C#</li>
<li>Utilice el método `PostWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>NET Framework 4.5.2 o más reciente</li>
<li>Net Standard 2.0 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
