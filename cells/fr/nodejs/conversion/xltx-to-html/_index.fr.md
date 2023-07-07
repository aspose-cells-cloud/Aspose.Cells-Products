---
title: XLTX en HTML Convertir API pour NodeJS
description:  Utilisation du SDK Cloud Aspose.Cells pour NodeJS pour convertir le fichier au format XLTX en fichier au format HTML.
url: /fr/nodejs/conversion/xltx-to-html/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API pour convertir XLTX en HTML" h2="Bibliothèque NodeJS pour convertir XLTX en HTML" p="Utilisez Cells Conversion REST API pour créer des workflows de feuille de calcul personnalisés dans NodeJS. Il s\'agit d\'une solution professionnelle pour convertir XLTX en HTML et d\'autres formats de documents en ligne à l\'aide de NodeJS." urlsection="conversion/xltx-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier XLTX en HTML dans NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLTX en HTML est une tâche complexe. Toutes les transitions de format XLTX vers HTML sont effectuées par notre SDK NodeJS tout en conservant le contenu structurel et logique principal de la feuille de calcul XLTX source. Notre bibliothèque NodeJS est une solution professionnelle pour convertir en ligne des fichiers XLTX vers HTML. Ce SDK Cloud offre aux développeurs NodeJS des fonctionnalités puissantes et une sortie HTML parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans NodeJS utilisant REST API pour convertir XLTX au format HTML" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xltx"),
        format: "html",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le nœud API pour convertir XLTX en HTML" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode cellsWorkbookPutConvertWorkbook pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>nœud v6.17.1 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
