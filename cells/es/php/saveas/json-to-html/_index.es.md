---
title:  Guarde JSON como HTML usando PHP
description:  Utilizando Aspose.Cells Cloud SDK para PHP para guardar el archivo en formato JSON como archivo en formato HTML.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Guarde JSON como HTML" h2="Biblioteca PHP para guardar JSON como HTML" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en PHP. Esta es una solución profesional para guardar JSON como HTML y otros formatos de documentos en línea usando PHP." urlsection="saveas/json-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo JSON como HTML en PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de JSON como HTML es una tarea compleja. Todas las transiciones de formato JSON a HTML las realiza nuestro SDK PHP mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo JSON de origen. Nuestra biblioteca PHP es una solución profesional para guardar JSON como archivos HTML en línea. Este SDK de nube ofrece a los desarrolladores de PHP una funcionalidad potente y un resultado de HTML perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP Ejemplo de código para guardar JSON como HTML usando REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.json';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "html";
    $newfilename = "Book1Saveas.html";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para PHP para guardar archivos Excel en otros formatos JSON como HTML" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `PostWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>PHP 7.4 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
