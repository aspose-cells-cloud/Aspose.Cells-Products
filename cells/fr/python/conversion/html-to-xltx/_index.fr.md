﻿---
title: HTML à XLTX Convertir API pour Python
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/python/conversion/html-to-xltx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API pour convertir HTML en XLTX" h2="bibliothèque Python pour convertir HTML en XLTX" p="Utilisez Cells Conversion REST API pour créer des flux de travail de feuille de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour convertir HTML en XLTX et d\'autres formats de documents en ligne à l\'aide de Python." urlsection="conversion/html-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier HTML en XLTX en Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de HTML en XLTX est une tâche complexe. Toutes les transitions du format HTML vers XLTX sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul source HTML. Notre bibliothèque Python est une solution professionnelle pour convertir en ligne des fichiers HTML en fichiers XLTX. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie XLTX parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Python utilisant REST API pour convertir HTML au format XLTX" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.html",format="xltx")
    shutil.move(file1, "destFile.xltx")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Python API pour convertir HTML en XLTX" >}}
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