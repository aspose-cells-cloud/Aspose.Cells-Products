---
title:  Convierta HTML a GIF usando C#
description:  Utilizar el SDK de Cloud Aspose.Cells para C# para convertir un archivo de formato HTML a un archivo de formato GIF.
kwords: Excel, Convert HTML to GIF, REST, C#
howto: How to convert HTML to GIF using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir HTML a GIF" h2="Biblioteca C# para convertir HTML a GIF" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos Net. Esta es una solución profesional para convertir HTML a GIF y otros formatos de documentos en línea usando C#." urlsection="conversion/html-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta HTML a GIF usando Cells Cloud SDK para C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de HTML a GIF puede ser una tarea compleja. Nuestro SDK C# maneja todas las conversiones de formato HTML a GIF preservando al mismo tiempo el contenido estructural y lógico principal de la hoja de cálculo HTML de origen. Nuestra biblioteca C# proporciona una solución profesional para convertir archivos HTML a GIF en línea. Este SDK de nube brinda a los desarrolladores C# una potente funcionalidad y garantiza una salida GIF de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Ejemplo de código para convertir HTML a GIF usando Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.html";
    string format = "gif";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.gif";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir HTML a GIF usando la biblioteca Cells Cloud Net." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca C# y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en C#</li>
<li>Utilice el método `PutConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>NET Framework 4.5.2 o más reciente</li>
<li>Net Standard 2.0 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
