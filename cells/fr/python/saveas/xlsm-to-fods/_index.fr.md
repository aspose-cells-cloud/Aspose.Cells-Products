---
title: Enregistrez XLSM sous FODS API pour Python
description:  Utilisation du SDK Cloud Aspose.Cells pour Python pour enregistrer le fichier au format XLSM en tant que fichier au format FODS.
url: /fr/python/saveas/xlsm-to-fods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API pour enregistrer XLSM en tant que FODS" h2="bibliothèque Python pour enregistrer XLSM en tant que FODS" p="Utilisez Cells SaveAs REST API pour créer des workflows de feuille de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour enregistrer XLSM en tant que FODS et d\'autres formats de documents en ligne à l\'aide de Python." urlsection="saveas/xlsm-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrer un fichier XLSM sous FODS au Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement de formats de fichiers à partir de XLSM en tant que FODS est une tâche complexe. Toutes les transitions de format XLSM vers FODS sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSM source. Notre bibliothèque Python est une solution professionnelle pour enregistrer en ligne des fichiers XLSM en tant que FODS. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie FODS parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Python utilisant REST API pour enregistrer XLSM au format FODS" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsm'    
    saveOptions = None
    newfilename = "Book1Saveas.fods"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Python API pour enregistrer XLSM en tant que FODS" >}}
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
