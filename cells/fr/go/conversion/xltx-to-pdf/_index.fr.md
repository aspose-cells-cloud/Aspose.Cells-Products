---
title:  Convertir XLTX en PDF à l'aide de Go
description:  Utilisation du SDK Cloud Aspose.Cells pour Go pour convertir un fichier au format XLTX en fichier au format PDF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir XLTX en PDF" h2="Accédez à la bibliothèque pour convertir XLTX en PDF" p="Utilisez la conversion API de Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans les projets Go. Il s\'agit d\'une solution professionnelle pour convertir XLTX en PDF et d\'autres formats de documents en ligne à l\'aide de Go." urlsection="conversion/xltx-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez XLTX en PDF à l\'aide du SDK Cloud Cells pour Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de XLTX en PDF peut être une tâche complexe. Notre SDK Go gère toutes les conversions du format XLTX vers PDF tout en préservant le contenu structurel et logique principal de la feuille de calcul XLTX source. Notre bibliothèque Go fournit une solution professionnelle pour convertir en ligne des fichiers XLTX en PDF. Ce SDK Cloud offre aux développeurs Go des fonctionnalités puissantes et garantit une sortie PDF de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Go Exemple de code pour convertir XLTX en PDF à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.xltx")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "pdf"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.pdf")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Cells Cloud SDK for Go pour convertir des fichiers Excel vers d\'autres formats XLTX en PDF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `PutConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>aller à la version go1.13.0 ou plus récente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
