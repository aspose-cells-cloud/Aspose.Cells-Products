---
title:  Enregistrez les NUMÉROS en tant qu'ODS en utilisant le Python.
description:  Utilisation du SDK Cloud Aspose.Cells pour Python pour enregistrer le fichier au format NUMBERS en tant que fichier au format ODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer les NUMÉROS en tant qu\'ODS" h2="Bibliothèque Python pour enregistrer des NUMÉROS sous forme d\'ODS" p="Utilisez SaveAs API de Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour enregistrer des NUMÉROS au format ODS et d\'autres formats de documents en ligne à l\'aide de Python." urlsection="saveas/numbers-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier NUMBERS sous ODS dans Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de NUMBERS en tant qu'ODS est une tâche complexe. Toutes les transitions du format NUMBERS vers ODS sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul NUMBERS source. Notre bibliothèque Python est une solution professionnelle pour enregistrer des NUMBERS sous forme de fichiers ODS en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie ODS parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Exemple de code pour enregistrer des NUMBERS en tant qu\'ODS à l\'aide de REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.numbers'    
    saveOptions = None
    newfilename = "Book1Saveas.ods"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Python pour enregistrer les fichiers Excel sous d\'autres formats NUMBERS en tant qu\'ODS" >}}
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
