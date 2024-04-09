---
title:  Convierta MHTML a JPG usando C#
description:  Utilizar el SDK de la nube Aspose.Cells para C# para convertir un archivo de formato MHTML a un archivo de formato JPG.
kwords: Excel, Convert MHTML to JPG, REST, C#
howto: How to convert MHTML to JPG using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir MHTML a JPG" h2="Biblioteca C# para convertir MHTML a JPG" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos Net. Esta es una solución profesional para convertir MHTML a JPG y otros formatos de documentos en línea usando C#." urlsection="conversion/mhtml-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta MHTML a JPG usando Cells Cloud SDK para C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de MHTML a JPG puede ser una tarea compleja. Nuestro SDK C# maneja todas las conversiones de formato MHTML a JPG preservando al mismo tiempo el contenido estructural y lógico principal de la hoja de cálculo MHTML de origen. Nuestra biblioteca C# proporciona una solución profesional para convertir archivos MHTML a JPG en línea. Este SDK de nube brinda a los desarrolladores C# una potente funcionalidad y garantiza una salida JPG de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Ejemplo de código para convertir MHTML a JPG usando Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.mhtml";
    string format = "jpg";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.jpg";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir MHTML a JPG usando la biblioteca Cells Cloud Net." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca C# y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en C#</li>
<li>Utilice el método `PutConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>NET Framework 4.5.2 o más reciente</li>
<li>Net Standard 2.0 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
