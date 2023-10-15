---
title: Enregistrez XLTX au format JPG en utilisant Python
description:  Utilisation du SDK Cloud Aspose.Cells pour Python pour enregistrer le fichier au format XLTX au format JPG.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer XLTX au format JPG" h2="Bibliothèque Python pour enregistrer XLTX au format JPG" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour enregistrer XLTX au format JPG et d\'autres formats de document en ligne à l\'aide de Python." urlsection="saveas/xltx-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier XLTX au format JPG dans Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers XLTX au format JPG est une tâche complexe. Toutes les transitions du format XLTX vers JPG sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul XLTX source. Notre bibliothèque Python est une solution professionnelle pour enregistrer XLTX sous forme de fichiers JPG en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie JPG parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Exemple de code pour enregistrer XLTX au format JPG à l\'aide de REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xltx'    
    saveOptions = None
    newfilename = "Book1Saveas.jpg"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Python pour enregistrer les fichiers Excel sous d\'autres formats XLTX au format JPG" >}}
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
