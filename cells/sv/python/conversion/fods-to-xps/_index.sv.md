---
title:  Convertir de Excel FODS a XPS via Python
description: Cree, edite o convierta archivos Excel con REST API y Open Source Python SDK
url: /sv/python/conversion/fods-to-xps/
family: cells
platformtag: python
feature: conversion
informat: FODS
outformat: XPS
platform: Python
otherformats: XLTM DIF PDF MD SVG TIFF HTML XLTX TSV XLS CSV FODS XLSX XML XLSB XPS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convierta FODS a XPS con Python" h2="Lea, edite y exporte datos Excel a otros formatos con Cloud SDK de código abierto para Python" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS a XPS Conversión con Python" %}}
1.  Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización
1. Inicialice ```CellsApi``` con ID de cliente, Secreto de cliente, URL base y versión API
1. Cargue el archivo FODS al almacenamiento en la nube predeterminado con el método ```CellsApi.upload_file```
1. Llame al método ```CellsApi.cells_save_as_post_document_save_as``` para obtener el archivo XPS resultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Comience con Excel API y Python SDK" %}}
 Obtenga Excel Cloud SDK para el código fuente Python de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python) para compilar el SDK usted mismo o diríjase a la[Lanzamientos](https://releases.aspose.cloud/) para opciones de descarga alternativas.

 También eche un vistazo a Swagger-based[API Referencia](https://apireference.aspose.cloud/cells/) para saber más sobre el[Excel DESCANSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Python Código para FODS a XPS Conversión" gistPath="" %}}
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python
import os
import sys
import asposecellscloud
from asposecellscloud.apis.cells_api import CellsApi
api  = asposecellscloud.apis.cells_api.CellsApi(os.getenv('CellsCloudClientId'), os.getenv('CellsCloudClientSecret'), "v3.0" ,os.getenv('CellsCloudApiBaseUrl'))

name ='template.fods'    
saveOptions = None
newfilename = "output.xps"
isAutoFitRows= True
isAutoFitColumns= True
folder = "temp"
result = api.upload_file(folder + '/' + name,  "c:/TestData/" + name)
 
result = api.cells_save_as_post_document_save_as(name, save_options=saveOptions, newfilename=(folder +'/' + newfilename), is_auto_fit_rows=isAutoFitRows, is_auto_fit_columns=isAutoFitColumns, folder=folder)
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}