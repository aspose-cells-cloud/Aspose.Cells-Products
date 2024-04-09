---
title:  Exporte la HOJA DE TRABAJO a EMF desde Excel usando Cells Cloud SDK para PHP
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} usando {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportar HOJA DE TRABAJO a EMF desde Excel" h2="Biblioteca PHP para exportar HOJA DE TRABAJO al archivo EMF" p="Utilice Exportar API de Cells Cloud para exportar flujos de trabajo de objetos internos de archivos Excel en PHP. Esta es una solución profesional para exportar HOJA DE TRABAJO a un archivo de formato EMF desde una hoja de cálculo en línea usando PHP." urlsection="export/worksheet-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporte el objeto WORKSHEET a un archivo de formato EMF usando Cells Cloud SDK para PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar el objeto WORKSHEET al archivo EMF desde el archivo Excel es una tarea compleja. Nuestro SDK PHP realiza la exportación de transiciones de HOJA DE TRABAJO a formato EMF mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo de HOJA DE TRABAJO de origen. Nuestra biblioteca PHP es una solución profesional para exportar objetos HOJA DE TRABAJO a archivos con formato EMF en línea. Este SDK de nube ofrece a los desarrolladores de PHP una funcionalidad potente y un resultado de EMF perfecto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código en PHP usando REST API para exportar HOJA DE TRABAJO al formato EMF desde una hoja de cálculo" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'worksheet', 'emf' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para PHP para exportar objetos de Excel WORKSHEET a EMF" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `postExport` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>PHP 7.4 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
