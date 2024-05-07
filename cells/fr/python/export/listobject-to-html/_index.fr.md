---
title:  Exportez LISTOBJECT vers HTML à partir de Excel à l'aide du SDK Cloud Cells pour Python
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords: Excel, listobject, html, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to HTML","description": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to HTML","image": {"@type": "ImageObject"},"url": "/python/export/listobject-to-html/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to HTML step 1", "image": {"@type": "ImageObject",},"url": "/python/export/listobject-to-html/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to HTML step 1", "image": {"@type": "ImageObject",},"url": "/python/export/listobject-to-html/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to HTML step 1", "image": {"@type": "ImageObject",},"url": "/python/export/listobject-to-html/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter LISTOBJECT vers HTML à partir de Excel" h2="Bibliothèque Python pour exporter LISTOBJECT vers le fichier HTML" p="Utilisez Export API de Cells Cloud pour exporter les flux de travail d\'objets internes du fichier Excel dans Python. Il s\'agit d\'une solution professionnelle pour exporter LISTOBJECT au format HTML à partir d\'une feuille de calcul en ligne à l\'aide de Python." urlsection="export/listobject-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportez l\'objet LISTOBJECT vers un fichier au format HTML à l\'aide du SDK Cloud Cells pour Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet LISTOBJECT vers le fichier HTML à partir du fichier Excel est une tâche complexe. L'exportation des transitions de LISTOBJECT vers le format HTML est effectuée par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul LISTOBJECT source. Notre bibliothèque Python est une solution professionnelle pour exporter des objets LISTOBJECT vers des fichiers au format HTML en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie HTML parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans Python utilisant REST API pour exporter LISTOBJECT au format HTML à partir d\'une feuille de calcul" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"listobject","html")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Python pour exporter des objets de Excel LISTOBJECT vers HTML" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Appelez la méthode post_export pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Python 2.7 ou plus récent</li>
<li>Python 3.10 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
