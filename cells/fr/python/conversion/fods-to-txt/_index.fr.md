---
title:  Convertir de Excel FODS en TXT via Python
description: Créez, modifiez ou convertissez des fichiers Excel avec le SDK REST API et Open Source Python
url: /fr/python/conversion/fods-to-txt/
family: cells
platformtag: python
feature: conversion
informat: FODS
outformat: TXT
platform: Python
otherformats: XLTM MD XPS FODS MHTML CSV SVG DIF TIFF TXT XLSM PDF XLSX XLTX TSV XLSB 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertissez FODS en TXT avec Python" h2="Lisez, modifiez et exportez les données Excel vers d\'autres formats avec le SDK Cloud open source pour Python" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion FODS en TXT avec Python" %}}
1.  Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API
1. Initialisez ```CellsApi``` avec l'ID client, le secret client, l'URL de base et la version API
1. Téléchargez le fichier FODS sur Cloud Storage par défaut avec la méthode ```CellsApi.upload_file```
1. Appelez la méthode ```CellsApi.cells_save_as_post_document_save_as``` pour obtenir le fichier TXT résultant
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Premiers pas avec les SDK Excel, API et Python" %}}
 Obtenez le SDK Cloud Excel pour le code source Python à partir de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python) pour compiler le SDK vous-même ou rendez-vous sur[Sorties](https://releases.aspose.cloud/) pour des options de téléchargement alternatives.

 Jetez également un œil à Swagger-based[API Référence](https://apireference.aspose.cloud/cells/) pour en savoir plus sur le[Excel REPOS API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Python Code pour la conversion FODS en TXT" gistPath="" %}}
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python
import os
import sys
import asposecellscloud
from asposecellscloud.apis.cells_api import CellsApi
api  = asposecellscloud.apis.cells_api.CellsApi(os.getenv('CellsCloudClientId'), os.getenv('CellsCloudClientSecret'), "v3.0" ,os.getenv('CellsCloudApiBaseUrl'))

name ='template.fods'    
saveOptions = None
newfilename = "output.txt"
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