---
title:  Convierta FODS a XPS en la nube via PHP
description: Cree, edite o convierta archivos Excel con REST API y Open Source PHP SDK
url: /es/php/conversion/fods-to-xps/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: XPS
platform: PHP
otherformats: XLSB SVG TSV HTML XLSM ODS DIF MHTML PDF XLTX FODS XLTM CSV XPS TXT TIFF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convierta FODS a XPS con PHP" h2="Automatice la conversión de archivos Excel y OpenOffice con el SDK de nube de código abierto para PHP" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Convierta rápidamente FODS a XPS via PHP" %}}
1.  Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización
1. Inicialice ```CellsApi``` con ID de cliente, secreto de cliente, URL base y versión API
1. Cargue el archivo FODS al Cloud Storage predeterminado con el método ```CellsApi.uploadFile```
1. Llame al ```CellsApi.cellsSaveAsPostDocumentSaveAs``` para obtener el archivo XPS resultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Comience con Excel API y PHP SDK" %}}
 Obtenga Excel Cloud SDK para el código fuente PHP de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) para compilar el SDK usted mismo o diríjase al[Lanzamientos](https://releases.aspose.cloud/) para opciones de descarga alternativas.

 También eche un vistazo a Basado en Swagger[API Referencia](https://apireference.aspose.cloud/cells/) para saber más sobre el[Excel DESCANSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Código PHP para conversión de FODS a XPS" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.xps";
$isAutoFitRows= 'true';
$isAutoFitColumns= 'true';
$folder = "Temp";
CellsApi::ready( $this->instance, $name, $folder );
$result = $this->instance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename, $isAutoFitRows, $isAutoFitColumns, $folder);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}