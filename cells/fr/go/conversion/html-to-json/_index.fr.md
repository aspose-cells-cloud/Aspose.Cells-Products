﻿---
title:  HTML en JSON Convertir API pour Go
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/go/conversion/html-to-json/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Allez API pour convertir HTML en JSON" h2="Accédez à la bibliothèque pour convertir HTML en JSON" p="Utilisez Cells Conversion REST API pour créer des workflows de feuille de calcul personnalisés dans Go. Il s\'agit d\'une solution professionnelle pour convertir HTML en JSON et d\'autres formats de documents en ligne à l\'aide de Go." urlsection="conversion/html-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier HTML en JSON dans Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de HTML en JSON est une tâche complexe. Toutes les transitions du format HTML au format JSON sont effectuées par notre SDK Go tout en conservant le contenu structurel et logique principal de la feuille de calcul source HTML. Notre bibliothèque Go est une solution professionnelle pour convertir en ligne des fichiers HTML en fichiers JSON. Ce SDK Cloud offre aux développeurs Go des fonctionnalités puissantes et une sortie JSON parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Go utilisant REST API pour convertir HTML au format JSON" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.html")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "json"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.json")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Go API pour convertir HTML en JSON" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode CellsWorkbookPutConvertWorkbook pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>go version go1.13.0 ou plus récente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}