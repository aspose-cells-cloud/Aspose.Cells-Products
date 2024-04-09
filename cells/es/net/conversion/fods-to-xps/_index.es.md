---
title: Convierta FODS a XPS usando C#
description:  Utilizar el SDK de la nube Aspose.Cells para C# para convertir un archivo de formato FODS a un archivo de formato XPS.
kwords: Excel, Convert FODS to XPS, REST, C#
howto: How to convert FODS to XPS using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir FODS a XPS" h2="Biblioteca C# para convertir FODS a XPS" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos Net. Esta es una solución profesional para convertir FODS a XPS y otros formatos de documentos en línea usando C#." urlsection="conversion/fods-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta FODS a XPS usando Cells Cloud SDK para C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de FODS a XPS puede ser una tarea compleja. Nuestro SDK C# maneja todas las conversiones de formato FODS a XPS y al mismo tiempo conserva el contenido estructural y lógico principal de la hoja de cálculo FODS de origen. Nuestra biblioteca C# proporciona una solución profesional para convertir archivos FODS a XPS en línea. Este SDK de nube brinda a los desarrolladores de C# una potente funcionalidad y garantiza resultados de XPS de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Ejemplo de código para convertir FODS a XPS usando Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.fods";
    string format = "xps";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xps";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir FODS a XPS usando la biblioteca Cells Cloud Net." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca C# y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en C#</li>
<li>Utilice el método `PutConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>NET Framework 4.5.2 o más reciente</li>
<li>Net Standard 2.0 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
