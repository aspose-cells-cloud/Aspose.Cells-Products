---
title:  Enregistrez CSV au format MHTML en utilisant Python
description:  Utilisation du SDK Cloud Aspose.Cells pour Python pour enregistrer le fichier au format CSV au format MHTML.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer CSV au format MHTML" h2="Bibliothèque Python pour enregistrer CSV au format MHTML" p="Utilisez SaveAs API de Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour enregistrer CSV au format MHTML et d\'autres formats de document en ligne à l\'aide de Python." urlsection="saveas/csv-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier CSV au format MHTML dans Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers CSV au format MHTML est une tâche complexe. Toutes les transitions du format CSV vers MHTML sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul CSV source. Notre bibliothèque Python est une solution professionnelle pour enregistrer des fichiers CSV sous forme de fichiers MHTML en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie MHTML parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Exemple de code pour enregistrer un fichier CSV au format MHTML à l\'aide de REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.csv'    
    saveOptions = None
    newfilename = "Book1Saveas.mhtml"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Python pour enregistrer les fichiers Excel sous d\'autres formats CSV comme MHTML" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `post_workbook_save_as` pour récupérer le flux résultant.</li>
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
