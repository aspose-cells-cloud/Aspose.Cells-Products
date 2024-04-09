---
title:  Guarde XLS como XLSB usando PHP
description:  Utilizando Aspose.Cells Cloud SDK para PHP para guardar el archivo en formato XLS como archivo en formato XLSB.
kwords: Excel, Save XLS as XLSB, REST, PHP
howto: How to save XLS as XLSB using Aspose.Cells Cloud PHP library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar XLS como XLSB" h2="Biblioteca PHP para guardar XLS como XLSB" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en PHP. Esta es una solución profesional para guardar XLS como XLSB y otros formatos de documentos en línea usando PHP." urlsection="saveas/xls-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo XLS como XLSB en PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLS como XLSB es una tarea compleja. Todas las transiciones de formato XLS a XLSB se realizan mediante nuestro SDK PHP manteniendo el contenido estructural y lógico principal de la hoja de cálculo XLS de origen. Nuestra biblioteca PHP es una solución profesional para guardar archivos XLS como XLSB en línea. Este SDK de nube ofrece a los desarrolladores de PHP una potente funcionalidad y una salida XLSB perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Ejemplo de código para guardar XLS como XLSB usando REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xls';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "xlsb";
    $newfilename = "Book1Saveas.xlsb";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo guardar XLS como XLSB usando la biblioteca Cells Cloud PHP." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca PHP y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en PHP.</li>
<li>Utilice el método `PostWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>PHP 7.4 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
