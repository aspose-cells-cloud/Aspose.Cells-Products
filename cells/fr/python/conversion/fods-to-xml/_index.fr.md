---
title:  Convertir FODS en XML à l'aide de Python
description:  Utilisation du SDK Cloud Aspose.Cells pour Python pour convertir un fichier au format FODS en fichier au format XML.
kwords: Excel, Convert FODS to XML, REST, Python
howto: How to convert FODS to XML using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir FODS en XML" h2="Bibliothèque Python pour convertir FODS en XML" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Python. Il s\'agit d\'une solution professionnelle pour convertir FODS en XML et d\'autres formats de documents en ligne à l\'aide du Python." urlsection="conversion/fods-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez FODS en XML à l\'aide du SDK Cloud Cells pour Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers FODS en XML peut être une tâche complexe. Notre SDK Python gère toutes les conversions du format FODS vers XML tout en préservant le contenu structurel et logique principal de la feuille de calcul FODS source. Notre bibliothèque Python fournit une solution professionnelle pour convertir en ligne des fichiers FODS en fichiers XML. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et garantit une sortie XML de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Exemple de code pour convertir FODS en XML à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.fods",format="xml")
    shutil.move(file1, "destFile.xml")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment convertir FODS en XML à l\'aide de la bibliothèque Cells Cloud Python." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Python et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Python.</li>
<li>Utilisez la méthode `put_convert_workbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Python 2.7 ou plus récent</li>
<li>Python 3.10 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
