---
title:  Enregistrez HTML sous XPS en utilisant Go
description:  Utilisation du SDK Cloud Aspose.Cells pour Go pour enregistrer le fichier au format HTML en tant que fichier au format XPS.
kwords: Excel, Save HTML as XPS, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save HTML as XPS using the Cells Cloud Go library.","description": "How to save HTML as XPS using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/html-to-xps/","step": [{ "@type": "HowToStep","name": "How to save HTML as XPS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/html-to-xps/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save HTML as XPS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/html-to-xps/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save HTML as XPS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/html-to-xps/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save HTML as XPS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/html-to-xps/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer le HTML sous le nom XPS" h2="Accédez à la bibliothèque pour enregistrer HTML sous le nom XPS" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans Go. Il s\'agit d\'une solution professionnelle pour enregistrer HTML sous XPS et d\'autres formats de documents en ligne à l\'aide de Go." urlsection="saveas/html-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrer un fichier HTML sous le nom XPS dans Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de HTML à XPS est une tâche complexe. Toutes les transitions de format HTML à XPS sont effectuées par notre SDK Go tout en conservant le contenu structurel et logique principal de la feuille de calcul source HTML. Notre bibliothèque Go est une solution professionnelle pour enregistrer HTML en tant que fichiers XPS en ligne. Ce SDK Cloud offre aux développeurs Go des fonctionnalités puissantes et une sortie XPS parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go Exemple de code pour enregistrer HTML sous XPS en utilisant REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.html"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xps"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment enregistrer HTML sous XPS à l\'aide de la bibliothèque Cloud Go Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Go et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en go.</li>
<li>Utilisez la méthode `PostWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>aller à la version go1.13.0 ou plus récente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
