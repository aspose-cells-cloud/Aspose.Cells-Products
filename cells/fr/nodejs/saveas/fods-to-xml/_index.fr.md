---
title:  Enregistrer FODS au format XML à l'aide de NodeJS
description:  Utilisation du SDK Cloud Aspose.Cells pour NodeJS pour enregistrer le fichier au format FODS en tant que fichier au format XML.
kwords: Excel, Save FODS as XML, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as XML using the Cells Cloud NodeJS library.","description": "How to save FODS as XML using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/saveas/fods-to-xml/","step": [{ "@type": "HowToStep","name": "How to save FODS as XML using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-xml/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as XML using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-xml/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as XML using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-xml/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to save FODS as XML using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-xml/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer FODS au format XML" h2="Bibliothèque NodeJS pour enregistrer FODS au format XML" p="Utilisez SaveAs API sur Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans NodeJS. Il s\'agit d\'une solution professionnelle pour enregistrer les FODS au format XML et autres formats de documents en ligne à l\'aide de NodeJS." urlsection="saveas/fods-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrer un fichier FODS au format XML dans NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers de FODS au format XML est une tâche complexe. Toutes les transitions du format FODS vers XML sont effectuées par notre SDK NodeJS tout en conservant le contenu structurel et logique principal de la feuille de calcul FODS source. Notre bibliothèque NodeJS est une solution professionnelle pour enregistrer les FODS sous forme de fichiers XML en ligne. Ce SDK Cloud offre aux développeurs NodeJS des fonctionnalités puissantes et une sortie XML parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code NodeJS pour enregistrer FODS au format XML à l\'aide de REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.fods",
      folder: "CellsTests",
      newfilename: "Book1Saveas.xml",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment enregistrer FODS au format XML à l\'aide de la bibliothèque Cloud NodeJS Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque NodeJS et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en JavaScript.</li>
<li>Utilisez la méthode `PostWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>nœud v6.17.1 ou version ultérieure</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
