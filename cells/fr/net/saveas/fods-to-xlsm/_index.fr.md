---
title:  Enregistrez FODS au format XLSM en utilisant C#
description:  Utilisation du SDK Cloud Aspose.Cells pour C# pour enregistrer le fichier au format FODS au format XLSM.
kwords: Excel, Save FODS as XLSM, REST, C#
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as XLSM using the Cells Cloud Net library.","description": "How to save FODS as XLSM using the Cells Cloud Net library.","image": {"@type": "ImageObject"},"url": "/net/saveas/fods-to-xlsm/","step": [{ "@type": "HowToStep","name": "How to save FODS as XLSM using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/fods-to-xlsm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as XLSM using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/fods-to-xlsm/","text": "Install C# library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as XLSM using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/fods-to-xlsm/","text": "Open the source file in C#",},{ "@type": "HowToStep","name": "How to save FODS as XLSM using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/fods-to-xlsm/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer FODS au format XLSM" h2="Bibliothèque C# pour enregistrer FODS au format XLSM" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Net. Il s\'agit d\'une solution professionnelle pour enregistrer les FODS au format XLSM et d\'autres formats de documents en ligne en utilisant le C#." urlsection="saveas/fods-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier FODS au format XLSM dans C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de FODS au format XLSM est une tâche complexe. Toutes les transitions du format FODS vers XLSM sont effectuées par notre SDK C# tout en conservant le contenu structurel et logique principal de la feuille de calcul FODS source. Notre bibliothèque C# est une solution professionnelle pour enregistrer les FODS sous forme de fichiers XLSM en ligne. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et une sortie XLSM parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Exemple de code pour enregistrer FODS au format XLSM à l\'aide de REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.fods";
    string newfilename = "Book1SaveAs.xlsm";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment enregistrer FODS au format XLSM à l\'aide de la bibliothèque Cloud Net Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque C# et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source dans C#</li>
<li>Utilisez la méthode `PostWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>NET Framework 4.5.2 ou version ultérieure</li>
<li>Net Standard 2.0 ou version ultérieure</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
