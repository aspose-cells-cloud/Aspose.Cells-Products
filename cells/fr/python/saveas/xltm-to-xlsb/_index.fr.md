---
title:  Enregistrez XLTM en tant que XLSB en utilisant Python
description: Utilisation du SDK Cloud Aspose.Cells pour Python pour enregistrer le fichier au format XLTM en tant que fichier au format XLSB.
kwords: Excel, Save XLTM as XLSB, REST, Python
howto: How to save XLTM as XLSB using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer XLTM sous XLSB" h2="Bibliothèque Python pour enregistrer XLTM au format XLSB" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour enregistrer XLTM au format XLSB et d\'autres formats de documents en ligne à l\'aide de Python." urlsection="saveas/xltm-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier XLTM au format XLSB dans Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de XLTM au format XLSB est une tâche complexe. Toutes les transitions du format XLTM vers XLSB sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul XLTM source. Notre bibliothèque Python est une solution professionnelle pour enregistrer XLTM sous forme de fichiers XLSB en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie XLSB parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Exemple de code pour enregistrer XLTM au format XLSB à l\'aide de REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xltm'    
    saveOptions = None
    newfilename = "Book1Saveas.xlsb"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment enregistrer XLTM au format XLSB à l\'aide de la bibliothèque Cells Cloud Python." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Python et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Python.</li>
<li>Utilisez la méthode `post_workbook_save_as` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Python 2.7 ou plus récent</li>
<li>Python 3.10 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
