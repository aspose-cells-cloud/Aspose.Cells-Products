---
title:  Exporte IMAGEN a GIF desde Excel usando Cells Cloud SDK para PHP
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} usando {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportar IMAGEN a GIF desde Excel" h2="Biblioteca PHP para exportar IMAGEN a archivo GIF" p="Utilice Exportar API de Cells Cloud para exportar flujos de trabajo de objetos internos de archivos Excel en PHP. Esta es una solución profesional para exportar archivos en formato IMAGEN a GIF desde una hoja de cálculo en línea usando PHP." urlsection="export/picture-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporte el objeto IMAGEN a un archivo en formato GIF usando Cells Cloud SDK para PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar un objeto IMAGEN a un archivo GIF desde el archivo Excel es una tarea compleja. La exportación de transiciones de IMAGEN a formato GIF se realiza mediante nuestro SDK PHP manteniendo el contenido estructural y lógico principal de la hoja de cálculo de IMAGEN de origen. Nuestra biblioteca PHP es una solución profesional para exportar objetos de IMAGEN a archivos en formato GIF en línea. Este SDK de nube ofrece a los desarrolladores de PHP una potente funcionalidad y una salida GIF perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código en PHP usando REST API para exportar IMAGEN a formato GIF desde una hoja de cálculo" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'picture', 'gif' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para PHP para exportar objetos de Excel IMAGEN a GIF" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `postExport` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>PHP 7.4 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
