---
title:  Convierta CSV a XML usando C#
description: Utilizar el SDK de Cloud Aspose.Cells para C# para convertir un archivo de formato CSV a un archivo de formato XML.
kwords: Excel, Convert CSV to XML, REST, C#
howto: How to convert CSV to XML using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir CSV a XML" h2="Biblioteca C# para convertir CSV a XML" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos Net. Esta es una solución profesional para convertir CSV a XML y otros formatos de documentos en línea usando C#." urlsection="conversion/csv-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta CSV a XML usando Cells Cloud SDK para C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de CSV a XML puede ser una tarea compleja. Nuestro SDK C# maneja todas las conversiones de formato CSV a XML y al mismo tiempo conserva el contenido estructural y lógico principal de la hoja de cálculo CSV de origen. Nuestra biblioteca C# proporciona una solución profesional para convertir archivos CSV a XML en línea. Este SDK de nube brinda a los desarrolladores C# una potente funcionalidad y garantiza una salida XML de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Ejemplo de código para convertir CSV a XML usando Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.csv";
    string format = "xml";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xml";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda a convertir CSV a XML utilizando la biblioteca Cloud Net Cells." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca C# y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en C#</li>
<li>Utilice el método `PutConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>NET Framework 4.5.2 o más reciente</li>
<li>Net Standard 2.0 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
