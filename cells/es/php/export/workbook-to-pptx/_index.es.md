﻿---
title:  Exportar LIBRO DE TRABAJO a PPTX desde una hoja de cálculo usando PHP API
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} mediante {2}.
url: /es/php/export/workbook-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API para exportar el LIBRO DE TRABAJO a un archivo PPTX" h2="PHP biblioteca para exportar LIBRO DE TRABAJO a archivo PPTX" p="Use Cells Export REST API para exportar flujos de trabajo de objetos internos de hoja de cálculo en PHP. Esta es una solución profesional para exportar WORKBOOK a un archivo de formato PPTX desde una hoja de cálculo en línea usando PHP." urlsection="export/workbook-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exporte el objeto WORKBOOK a un archivo de formato PPTX en PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar un objeto WORKBOOK a un archivo PPTX desde una hoja de cálculo es una tarea compleja. Exportar WORKBOOK a transiciones de formato PPTX se realiza mediante nuestro SDK PHP mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo WORKBOOK de origen. Nuestra biblioteca PHP es una solución profesional para exportar objetos de WORKBOOK a archivos de formato PPTX en línea. Este Cloud SDK ofrece a los desarrolladores de PHP una potente funcionalidad y una salida PPTX perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en PHP usando REST API para exportar WORKBOOK a formato PPTX desde una hoja de cálculo" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\LightCellsApi;
    $cells = new LightCellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $files = array (
        'DataSource' =>  "C:/datasource.xlsx",
        'AssemblyTest' => "C:/assemblytest.xlsx"
    );
    $result = $cells->postExport( $files,'workbook', 'pptx' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar PHP API para exportar WORKBOOK a PPTX" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método postExport para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>PHP 7.4 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}