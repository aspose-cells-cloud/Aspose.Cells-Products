---
title:  Enregistrez FODS en tant que MD en utilisant le Python
description:  Utilisation du SDK Cloud Aspose.Cells pour Python pour enregistrer le fichier au format FODS en tant que fichier au format MD.
kwords: Excel, Save FODS as MD, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as MD using the Cells Cloud Python library.","description": "How to save FODS as MD using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/fods-to-md/","step": [{ "@type": "HowToStep","name": "How to save FODS as MD using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/fods-to-md/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as MD using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/fods-to-md/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as MD using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/fods-to-md/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save FODS as MD using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/fods-to-md/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer FODS en tant que MD" h2="Bibliothèque Python pour enregistrer FODS en tant que MD" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Python. Il s\'agit d\'une solution professionnelle pour enregistrer les FODS au format MD et d\'autres formats de documents en ligne à l\'aide de Python." urlsection="saveas/fods-to-md/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier FODS en tant que MD dans Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de FODS en tant que MD est une tâche complexe. Toutes les transitions du format FODS vers MD sont effectuées par notre SDK Python tout en conservant le contenu structurel et logique principal de la feuille de calcul FODS source. Notre bibliothèque Python est une solution professionnelle pour enregistrer les FODS sous forme de fichiers MD en ligne. Ce SDK Cloud offre aux développeurs Python des fonctionnalités puissantes et une sortie MD parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Exemple de code pour enregistrer FODS en tant que MD à l\'aide de REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.fods'    
    saveOptions = None
    newfilename = "Book1Saveas.md"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment enregistrer FODS en tant que MD à l\'aide de la bibliothèque Cells Cloud Python." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Python et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Python.</li>
<li>Utilisez la méthode `post_workbook_save_as` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Python 2.7 ou plus récent</li>
<li>Python 3.10 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
