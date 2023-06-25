---
title:  Enregistrez XLSM sous EMF API pour NodeJS
description: Utilisation du SDK Cloud Aspose.Cells pour NodeJS pour enregistrer le fichier au format XLSM en tant que fichier au format EMF.
url: /fr/nodejs/saveas/xlsm-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API pour enregistrer XLSM sous EMF" h2="Bibliothèque NodeJS pour enregistrer XLSM sous EMF" p="Utilisez Cells SaveAs REST API pour créer des workflows de feuille de calcul personnalisés dans NodeJS. Il s\'agit d\'une solution professionnelle pour enregistrer XLSM sous EMF et d\'autres formats de documents en ligne à l\'aide de NodeJS." urlsection="saveas/xlsm-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier XLSM sous EMF dans NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers à partir de XLSM sous le nom EMF est une tâche complexe. Toutes les transitions de format XLSM vers EMF sont effectuées par notre SDK NodeJS tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSM source. Notre bibliothèque NodeJS est une solution professionnelle pour enregistrer en ligne des fichiers XLSM au format EMF. Ce SDK Cloud offre aux développeurs NodeJS des fonctionnalités puissantes et une sortie EMF parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans NodeJS utilisant REST API pour enregistrer XLSM au format EMF" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xlsm",
      folder: "CellsTests",
      newfilename: "Book1Saveas.emf",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le nœud API pour enregistrer XLSM sous EMF" >}}
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
