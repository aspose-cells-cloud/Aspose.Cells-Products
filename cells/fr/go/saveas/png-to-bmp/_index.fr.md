---
title:  Enregistrez PNG sous BMP en utilisant Go
description:  Utilisation du SDK Cloud Aspose.Cells pour Go pour enregistrer le fichier au format PNG en tant que fichier au format BMP.
kwords: Excel, Save PNG as BMP, REST, Go
howto: How to save PNG as BMP using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer le PNG sous le nom BMP" h2="Accédez à la bibliothèque pour enregistrer PNG sous le nom BMP" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans Go. Il s\'agit d\'une solution professionnelle pour enregistrer PNG sous BMP et d\'autres formats de documents en ligne à l\'aide de Go." urlsection="saveas/png-to-bmp/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrer un fichier PNG sous le nom BMP dans Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de PNG à BMP est une tâche complexe. Toutes les transitions de format PNG à BMP sont effectuées par notre SDK Go tout en conservant le contenu structurel et logique principal de la feuille de calcul source PNG. Notre bibliothèque Go est une solution professionnelle pour enregistrer PNG en tant que fichiers BMP en ligne. Ce SDK Cloud offre aux développeurs Go des fonctionnalités puissantes et une sortie BMP parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go Exemple de code pour enregistrer PNG sous BMP en utilisant REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.png"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.bmp"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment enregistrer PNG sous le nom BMP à l\'aide de la bibliothèque Cloud Go Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Go et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en go.</li>
<li>Utilisez la méthode `PostWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>aller à la version go1.13.0 ou plus récente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
