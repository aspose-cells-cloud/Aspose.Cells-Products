﻿---
title:  Enregistrez les NUMÉROS sous XLS API pour Go
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/go/saveas/numbers-to-xls/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Allez API pour enregistrer les NUMÉROS au format XLS" h2="Aller à la bibliothèque pour enregistrer les NUMÉROS au format XLS" p="Utilisez Cells SaveAs REST API pour créer des workflows de feuille de calcul personnalisés dans Go. Il s\'agit d\'une solution professionnelle pour enregistrer des NUMÉROS au format XLS et d\'autres formats de documents en ligne à l\'aide de Go." urlsection="saveas/numbers-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrer un fichier NUMBERS au format XLS dans Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement de formats de fichiers à partir de NUMBERS au format XLS est une tâche complexe. Toutes les transitions de format NUMBERS vers XLS sont effectuées par notre SDK Go tout en conservant le contenu structurel et logique principal de la feuille de calcul NUMBERS source. Notre bibliothèque Go est une solution professionnelle pour enregistrer des NUMÉROS sous forme de fichiers XLS en ligne. Ce SDK Cloud offre aux développeurs Go des fonctionnalités puissantes et une sortie XLS parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Go utilisant REST API pour enregistrer NUMBERS au format XLS" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.numbers"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xls"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Go API pour enregistrer des NUMÉROS au format XLS" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode CellsSaveAsPostDocumentSaveAs pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>go version go1.13.0 ou plus récente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}