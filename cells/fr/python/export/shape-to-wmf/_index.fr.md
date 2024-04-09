---
title:  Exportez SHAPE vers WMF à partir de Excel à l'aide du SDK Cloud Cells pour Python
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter SHAPE vers WMF à partir de Excel" h2="Bibliothèque Python pour exporter SHAPE vers un fichier WMF" p="Utilisez Export API de Cells Cloud pour exporter les flux de travail d\'objets internes du fichier Excel dans Python. Il s\'agit d\'une solution professionnelle pour exporter SHAPE vers un fichier au format WMF à partir d\'une feuille de calcul en ligne à l\'aide de Python." urlsection="export/shape-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportez l\'objet SHAPE vers un fichier au format WMF à l\'aide du SDK Cloud Cells pour Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet SHAPE vers le fichier WMF à partir du fichier Excel est une tâche complexe. L'exportation des transitions au format SHAPE vers WMF est effectuée par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul SHAPE source. Notre bibliothèque Python est une solution professionnelle pour exporter des objets SHAPE vers des fichiers au format WMF en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie WMF parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans Python utilisant REST API pour exporter SHAPE au format WMF à partir d\'une feuille de calcul" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import base64
    from asposecellscloud.apis.light_cells_api import LightCellsApi
    cells_api = LightCellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    files ={ 
        "myDocument.xlsx" :  "c:/myDocument.xlsx",
        "Book1.xlsx" :  "c:/Book1.xlsx" 
        }
    result = cells_api.post_export(files ,"shape","wmf")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Python pour exporter des objets de Excel SHAPE vers WMF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Appelez la méthode post_export pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Python 2.7 ou plus récent</li>
<li>Python 3.10 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
