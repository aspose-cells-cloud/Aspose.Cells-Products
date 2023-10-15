---
title:  Convertissez XLSB en XLTM en utilisant Python
description: Utilisation du SDK Cloud Aspose.Cells pour Python pour convertir un fichier au format XLSB en fichier au format XLTM.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir XLSB en XLTM" h2="Bibliothèque Python pour convertir XLSB en XLTM" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Python. Il s\'agit d\'une solution professionnelle pour convertir XLSB en XLTM et d\'autres formats de documents en ligne en utilisant le Python." urlsection="conversion/xlsb-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez XLSB en XLTM à l\'aide du SDK Cloud Cells pour Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLSB en XLTM peut être une tâche complexe. Notre SDK Python gère toutes les conversions du format XLSB vers XLTM tout en préservant le contenu structurel et logique principal de la feuille de calcul XLSB source. Notre bibliothèque Python fournit une solution professionnelle pour convertir des fichiers XLSB en XLTM en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et garantit une sortie XLTM de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Exemple de code pour convertir XLSB en XLTM à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlsb",format="xltm")
    shutil.move(file1, "destFile.xltm")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Python afin de convertir les fichiers Excel vers d\'autres formats XLSB en XLTM" >}}
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
