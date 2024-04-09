---
title:  Enregistrez XLSM au format DOCX en utilisant Python
description:  Utilisation du SDK Cloud Aspose.Cells pour Python pour enregistrer le fichier au format XLSM au format DOCX.
kwords: Excel, Save XLSM as DOCX, REST, Python
howto: How to save XLSM as DOCX using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer XLSM au format DOCX" h2="Bibliothèque Python pour enregistrer XLSM au format DOCX" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour enregistrer XLSM au format DOCX et d\'autres formats de documents en ligne à l\'aide de Python." urlsection="saveas/xlsm-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier XLSM au format DOCX dans Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers XLSM au format DOCX est une tâche complexe. Toutes les transitions du format XLSM vers DOCX sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSM source. Notre bibliothèque Python est une solution professionnelle pour enregistrer XLSM sous forme de fichiers DOCX en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie DOCX parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Exemple de code pour enregistrer XLSM au format DOCX à l\'aide de REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsm'    
    saveOptions = None
    newfilename = "Book1Saveas.docx"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment enregistrer XLSM au format DOCX à l\'aide de la bibliothèque Cells Cloud Python." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Python et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Python.</li>
<li>Utilisez la méthode `post_workbook_save_as` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Python 2.7 ou plus récent</li>
<li>Python 3.10 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
