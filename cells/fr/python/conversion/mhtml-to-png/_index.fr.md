﻿---
title:  MHTML en PNG Convertir API en Python
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/python/conversion/mhtml-to-png/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API pour convertir MHTML en PNG" h2="bibliothèque Python pour convertir MHTML en PNG" p="Utilisez Cells Conversion REST API pour créer des flux de travail de feuille de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour convertir MHTML en PNG et d\'autres formats de documents en ligne à l\'aide de Python." urlsection="conversion/mhtml-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier MHTML en PNG en Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de MHTML en PNG est une tâche complexe. Toutes les transitions de format MHTML vers PNG sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul MHTML source. Notre bibliothèque Python est une solution professionnelle pour convertir des fichiers MHTML en PNG en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie PNG parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Python utilisant REST API pour convertir MHTML au format PNG" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.mhtml",format="png")
    shutil.move(file1, "destFile.png")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Python API pour convertir MHTML en PNG" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Cellules d'appel_classeur_mettre_convertir_méthode de classeur pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Python 2.7 ou plus récent</li>
<li>Python 3.10 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}