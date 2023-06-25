---
title:  Convertir XML en DOCX API pour NodeJS
description:  Utilisation du SDK Cloud Aspose.Cells pour NodeJS pour convertir le fichier au format XML en fichier au format DOCX.
url: /fr/nodejs/conversion/xml-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API pour convertir XML en DOCX" h2="Bibliothèque NodeJS pour convertir XML en DOCX" p="Utilisez Cells Conversion REST API pour créer des workflows de feuille de calcul personnalisés dans NodeJS. Il s\'agit d\'une solution professionnelle pour convertir XML en DOCX et autres formats de documents en ligne à l\'aide de NodeJS." urlsection="conversion/xml-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier XML en DOCX dans NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion de formats de fichiers XML en DOCX est une tâche complexe. Toutes les transitions de format XML vers DOCX sont effectuées par notre SDK NodeJS tout en conservant le contenu structurel et logique principal de la feuille de calcul XML source. Notre bibliothèque NodeJS est une solution professionnelle pour convertir en ligne des fichiers XML en DOCX. Ce SDK Cloud offre aux développeurs NodeJS des fonctionnalités puissantes et une sortie DOCX parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans NodeJS utilisant REST API pour convertir XML au format DOCX" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xml"),
        format: "docx",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le nœud API pour convertir XML en DOCX" >}}
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
