---
title:  Convierta XLTM a DOCX usando PHP
description: Utilizar el SDK de la nube Aspose.Cells para PHP para convertir un archivo de formato XLTM a un archivo de formato DOCX.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir XLTM a DOCX" h2="Biblioteca PHP para convertir XLTM a DOCX" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en PHP proyectos. Esta es una solución profesional para convertir XLTM a DOCX y otros formatos de documentos en línea usando PHP." urlsection="conversion/xltm-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta XLTM a DOCX usando Cells Cloud SDK para PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de XLTM a DOCX puede ser una tarea compleja. Nuestro SDK PHP maneja todas las conversiones de formato XLTM a DOCX al tiempo que conserva el contenido estructural y lógico principal de la hoja de cálculo XLTM de origen. Nuestra biblioteca PHP proporciona una solución profesional para convertir archivos XLTM a DOCX en línea. Este SDK de nube brinda a los desarrolladores PHP una potente funcionalidad y garantiza una salida DOCX de alta calidad.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP Ejemplo de código para convertir XLTM a DOCX usando Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xltm';    
    $format ='docx';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.docx", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para PHP para convertir archivos Excel a otros formatos XLTM a DOCX" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `putConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>PHP 7.4 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
