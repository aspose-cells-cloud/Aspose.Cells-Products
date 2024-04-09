---
title:  Convertissez XLSM en FODS en utilisant Python
description:  Utilisation du SDK Cloud Aspose.Cells pour Python pour convertir un fichier au format XLSM en fichier au format FODS.
kwords: Excel, Convert XLSM to FODS, REST, Python
howto: How to convert XLSM to FODS using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir XLSM en FODS" h2="Bibliothèque Python pour convertir XLSM en FODS" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Python. Il s\'agit d\'une solution professionnelle pour convertir XLSM en FODS et d\'autres formats de documents en ligne en utilisant le Python." urlsection="conversion/xlsm-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez XLSM en FODS à l\'aide du SDK Cloud Cells pour Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLSM en FODS peut être une tâche complexe. Notre SDK Python gère toutes les conversions du format XLSM vers FODS tout en préservant le contenu structurel et logique principal de la feuille de calcul XLSM source. Notre bibliothèque Python fournit une solution professionnelle pour convertir des fichiers XLSM en FODS en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et garantit une sortie FODS de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Exemple de code pour convertir XLSM en FODS à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlsm",format="fods")
    shutil.move(file1, "destFile.fods")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment convertir XLSM en FODS à l\'aide de la bibliothèque Cells Cloud Python." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Python et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Python.</li>
<li>Utilisez la méthode `put_convert_workbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Python 2.7 ou plus récent</li>
<li>Python 3.10 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
