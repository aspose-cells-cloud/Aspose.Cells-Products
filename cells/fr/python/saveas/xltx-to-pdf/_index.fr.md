﻿---
title:  Enregistrez XLTX sous PDF API pour Python
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/python/saveas/xltx-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API pour enregistrer XLTX sous PDF" h2="Bibliothèque Python pour enregistrer XLTX sous PDF" p="Utilisez Cells SaveAs REST API pour créer des flux de travail de feuille de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour enregistrer XLTX sous PDF et d\'autres formats de documents en ligne à l\'aide de Python." urlsection="saveas/xltx-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier XLTX sous PDF dans Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers à partir de XLTX sous le nom PDF est une tâche complexe. Toutes les transitions de format XLTX vers PDF sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul XLTX source. Notre bibliothèque Python est une solution professionnelle pour enregistrer des fichiers XLTX sous PDF en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie PDF parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Python utilisant REST API pour enregistrer XLTX au format PDF" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xltx'    
    saveOptions = None
    newfilename = "Book1Saveas.pdf"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Python API pour enregistrer XLTX sous PDF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Cellules d'appel_sauvegarder_comme_poste_document_sauvegarder_comme méthode pour obtenir le flux résultant</li>
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