---
title:  Convertir PNG en SXC à l'aide de NodeJS
description: Utilisation du SDK Cloud Aspose.Cells pour NodeJS pour convertir un fichier au format PNG en fichier au format SXC.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir PNG en SXC" h2="Bibliothèque NodeJS pour convertir PNG en SXC" p="Utilisez la conversion API du Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans les projets NodeJS. Il s\'agit d\'une solution professionnelle pour convertir PNG en SXC et d\'autres formats de documents en ligne à l\'aide de NodeJS." urlsection="conversion/png-to-sxc/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez PNG en SXC à l\'aide du SDK Cloud Cells pour NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de PNG en SXC peut être une tâche complexe. Notre SDK NodeJS gère toutes les conversions du format PNG au format SXC tout en préservant le contenu structurel et logique principal de la feuille de calcul source PNG. Notre bibliothèque NodeJS fournit une solution professionnelle pour convertir en ligne PNG en fichiers SXC. Ce SDK Cloud offre aux développeurs NodeJS des fonctionnalités puissantes et garantit une sortie SXC de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code NodeJS pour convertir PNG en SXC à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.png"),
        format: "sxc",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Node pour convertir les fichiers Excel vers d\'autres formats PNG en SXC" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>nœud v6.17.1 ou version ultérieure</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
