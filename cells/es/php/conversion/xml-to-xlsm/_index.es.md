﻿---
title:  XML a XLSM Convertir API para PHP
description:  Usando Aspose.Cells Cloud SDK para PHP para convertir un archivo de formato XML a un archivo de formato XLSM.
url: /es/php/conversion/xml-to-xlsm/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API para convertir XML a XLSM" h2="PHP biblioteca para convertir XML a XLSM" p="Use Cells Conversion REST API para crear flujos de trabajo de hojas de cálculo personalizados en PHP. Esta es una solución profesional para convertir XML a XLSM y otros formatos de documentos en línea usando PHP." urlsection="conversion/xml-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta un archivo XML a XLSM en PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de XML a XLSM es una tarea compleja. Todas las transiciones de formato XML a XLSM se realizan mediante nuestro SDK PHP mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XML de origen. Nuestra biblioteca PHP es una solución profesional para convertir archivos XML a XLSM en línea. Este SDK de Cloud ofrece a los desarrolladores de PHP una potente funcionalidad y una salida XLSM perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en PHP usando REST API para convertir XML a formato XLSM" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xml';    
    $format ='xlsm';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xlsm", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar PHP API para convertir XML a XLSM" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método cellsWorkbookPutConvertWorkBook para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>PHP 7.4 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}