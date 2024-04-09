---
title:  Enregistrez TXT au format JPG en utilisant Python
description: Utilisation du SDK Cloud Aspose.Cells pour Python pour enregistrer le fichier au format TXT au format JPG.
kwords: Excel, Save TXT as JPG, REST, Python
howto: How to save TXT as JPG using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer TXT au format JPG" h2="Bibliothèque Python pour enregistrer TXT au format JPG" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour enregistrer TXT au format JPG et d\'autres formats de document en ligne à l\'aide de Python." urlsection="saveas/txt-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier TXT au format JPG dans Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers TXT au format JPG est une tâche complexe. Toutes les transitions du format TXT vers JPG sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul TXT source. Notre bibliothèque Python est une solution professionnelle pour enregistrer TXT sous forme de fichiers JPG en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie JPG parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Exemple de code pour enregistrer TXT au format JPG à l\'aide de REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.txt'    
    saveOptions = None
    newfilename = "Book1Saveas.jpg"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment enregistrer TXT au format JPG à l\'aide de la bibliothèque Cells Cloud Python." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Python et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Python.</li>
<li>Utilisez la méthode `post_workbook_save_as` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Python 2.7 ou plus récent</li>
<li>Python 3.10 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
