﻿---
title:  Konvertieren Sie FODS in SXC in der Cloud via PHP
description: Erstellen, bearbeiten oder konvertieren Sie Excel-Dateien mit REST API & Open Source PHP SDK
url: /de/php/conversion/fods-to-sxc/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: SXC
platform: PHP
otherformats: XLTX DIF XML PDF ODS MD XLSX TSV MHTML XLSB SVG TXT XLSM CSV XLTM TIFF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Wandeln Sie FODS mit PHP in SXC um" h2="Automatisieren Sie die Konvertierung von Excel- und OpenOffice-Dateien mit Open Source Cloud SDK für PHP" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertieren Sie FODS schnell in SXC via PHP" %}}
1.  Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten
1. Initialisieren Sie ```CellsApi``` mit Client-ID, Client-Geheimnis, Basis-URL und API-Version
1. Laden Sie die FODS-Datei mit der Methode ```CellsApi.uploadFile``` in den Standard-Cloud-Speicher hoch
1. Rufen Sie ```CellsApi.cellsSaveAsPostDocumentSaveAs``` an, um die resultierende SXC-Datei zu erhalten
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Beginnen Sie mit Excel API & PHP SDK" %}}
 Holen Sie sich Excel Cloud SDK für PHP-Quellcode von[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) um das SDK selbst zu kompilieren oder gehen Sie zur[Freigaben](https://releases.aspose.cloud/) für alternative Download-Optionen.

 Schauen Sie sich auch Swagger-basiert an[API Referenz](https://apireference.aspose.cloud/cells/) um mehr über die zu erfahren[Excel RUHE API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Code für die Umwandlung von FODS in SXC" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.sxc";
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