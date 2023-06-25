---
title:  Enregistrez les NUMÉROS sous PDF API pour NodeJS
description: Utilisation du SDK Cloud Aspose.Cells pour NodeJS pour enregistrer le fichier au format NUMBERS en tant que fichier au format PDF.
url: /fr/nodejs/saveas/numbers-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API pour enregistrer les NUMBERS sous PDF" h2="Bibliothèque NodeJS pour enregistrer NUMBERS sous PDF" p="Utilisez Cells SaveAs REST API pour créer des workflows de feuille de calcul personnalisés dans NodeJS. Il s\'agit d\'une solution professionnelle pour enregistrer des NUMBERS sous le nom PDF et d\'autres formats de documents en ligne à l\'aide de NodeJS." urlsection="saveas/numbers-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier NUMBERS sous le nom PDF dans NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers à partir de NUMBERS sous la forme PDF est une tâche complexe. Toutes les transitions de format NUMBERS vers PDF sont effectuées par notre SDK NodeJS tout en conservant le contenu structurel et logique principal de la feuille de calcul NUMBERS source. Notre bibliothèque NodeJS est une solution professionnelle pour enregistrer des fichiers NUMBERS en tant que PDF en ligne. Ce SDK Cloud offre aux développeurs NodeJS des fonctionnalités puissantes et une sortie PDF parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans NodeJS utilisant REST API pour enregistrer NUMBERS au format PDF" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.numbers",
      folder: "CellsTests",
      newfilename: "Book1Saveas.pdf",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le nœud API pour enregistrer des NUMÉROS sous PDF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode cellsSaveAsPostDocumentSaveAs pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>nœud v6.17.1 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
