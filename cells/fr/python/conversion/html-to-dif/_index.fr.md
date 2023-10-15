---
title:  Convertissez HTML en DIF en utilisant Python
description:  Utilisation du SDK Cloud Aspose.Cells pour Python pour convertir un fichier au format HTML en fichier au format DIF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir HTML en DIF" h2="Bibliothèque Python pour convertir HTML en DIF" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Python. Il s\'agit d\'une solution professionnelle pour convertir HTML en DIF et d\'autres formats de documents en ligne à l\'aide de Python." urlsection="conversion/html-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez HTML en DIF à l\'aide du SDK Cloud Cells pour Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de HTML en DIF peut être une tâche complexe. Notre SDK Python gère toutes les conversions du format HTML au format DIF tout en préservant le contenu structurel et logique principal de la feuille de calcul source HTML. Notre bibliothèque Python fournit une solution professionnelle pour convertir en ligne HTML en fichiers DIF. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et garantit une sortie DIF de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Exemple de code pour convertir HTML en DIF à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.html",format="dif")
    shutil.move(file1, "destFile.dif")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Python afin de convertir les fichiers Excel vers d\'autres formats HTML en DIF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `put_convert_workbook` pour récupérer le flux résultant.</li>
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
