---
title: Enregistrer XLSB au format CSV API pour Python
description:  Utiliser Aspose.Cells Cloud SDK pour Python pour enregistrer le fichier au format XLSB en tant que fichier au format CSV.
url: /fr/python/saveas/xlsb-to-csv/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API pour enregistrer XLSB au format CSV" h2="Bibliothèque Python pour enregistrer XLSB au format CSV" p="Utilisez Cells SaveAs REST API pour créer des flux de travail de feuille de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour enregistrer XLSB au format CSV et d\'autres formats de document en ligne à l\'aide de Python." urlsection="saveas/xlsb-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrer un fichier XLSB au format CSV au Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement de formats de fichiers XLSB au format CSV est une tâche complexe. Toutes les transitions de format XLSB à CSV sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSB source. Notre bibliothèque Python est une solution professionnelle pour enregistrer en ligne des fichiers XLSB sous forme de fichiers CSV. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie CSV parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Python utilisant REST API pour enregistrer XLSB au format CSV" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsb'    
    saveOptions = None
    newfilename = "Book1Saveas.csv"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Python API pour enregistrer XLSB au format CSV" >}}
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
