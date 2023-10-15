---
title:  Enregistrez TXT sous HTML à l'aide de Go
description:  Utilisation du SDK Cloud Aspose.Cells pour Go pour enregistrer le fichier au format TXT au format HTML.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer le TXT sous le numéro HTML" h2="Accédez à la bibliothèque pour enregistrer TXT sous le numéro HTML" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans Go. Il s\'agit d\'une solution professionnelle pour enregistrer TXT sous le numéro HTML et d\'autres formats de documents en ligne à l\'aide de Go." urlsection="saveas/txt-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier TXT sous le nom HTML dans Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers à partir de TXT sous le nom HTML est une tâche complexe. Toutes les transitions du format TXT vers HTML sont effectuées par notre SDK Go tout en conservant le contenu structurel et logique principal de la feuille de calcul TXT source. Notre bibliothèque Go est une solution professionnelle pour enregistrer TXT sous forme de fichiers HTML en ligne. Ce SDK Cloud offre aux développeurs Go des fonctionnalités puissantes et une sortie HTML parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Go Exemple de code pour enregistrer TXT sous HTML en utilisant REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.txt"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.html"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Go pour enregistrer les fichiers Excel sous d\'autres formats TXT sous le nom HTML" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `PostWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>aller à la version go1.13.0 ou plus récente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
