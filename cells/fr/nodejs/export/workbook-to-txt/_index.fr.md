﻿---
title:  Exporter WORKBOOK vers TXT à partir d'une feuille de calcul à l'aide de NodeJS API
description: Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers Excel et d'objets internes vers des types de fichiers de format. SDK prend en charge les types de langages de développement. Ils incluent Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby et Swift.
url: /fr/nodejs/export/workbook-to-txt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API pour exporter WORKBOOK vers un fichier TXT" h2="Bibliothèque NodeJS pour exporter WORKBOOK vers un fichier TXT" p="Utilisez Cells Export REST API pour exporter les workflows d\'objets internes de feuille de calcul dans NodeJS. Il s\'agit d\'une solution professionnelle pour exporter un fichier au format WORKBOOK vers TXT à partir d\'une feuille de calcul en ligne à l\'aide de NodeJS." urlsection="export/workbook-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exporter l\'objet WORKBOOK vers un fichier au format TXT dans NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
L'exportation d'un objet WORKBOOK vers un fichier TXT à partir d'une feuille de calcul est une tâche complexe. L'exportation des transitions de format WORKBOOK vers TXT est effectuée par notre SDK NodeJS tout en conservant le contenu structurel et logique principal de la feuille de calcul WORKBOOK source. Notre bibliothèque NodeJS est une solution professionnelle pour exporter en ligne des objets WORKBOOK vers des fichiers au format TXT. Ce SDK Cloud offre aux développeurs NodeJS des fonctionnalités puissantes et une sortie TXT parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans NodeJS utilisant REST API pour exporter WORKBOOK au format TXT à partir d\'une feuille de calcul" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { LightCellsApi, PostExportRequest } = require("asposecellscloud");
    const localPath = "C:/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new LightCellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    const AssemblyTestXlsx = "assemblytest.xlsx";
    var dataAssemblyTestXlsx =fs.createReadStream(localPath  + AssemblyTestXlsx);
    const DataSourceXlsx = "datasource.xlsx";
    var dataDataSourceXlsx =fs.createReadStream(localPath  + DataSourceXlsx);
    var req = new PostExportRequest({
      file:{AssemblyTestXlsx:dataAssemblyTestXlsx ,DataSourceXlsx:dataDataSourceXlsx },
      objectType : "workbook",
      format: "txt",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le nœud API pour exporter WORKBOOK vers TXT" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode postExport pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>nœud v6.17.1 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}