---
title:  Exportez WORKBOOK vers PNG à partir de Excel à l'aide du SDK Cloud Cells pour NodeJS
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords: Excel, workbook, png, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to PNG","description": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to PNG","image": {"@type": "ImageObject"},"url": "/nodejs/export/workbook-to-png/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to PNG step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to PNG step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-png/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to PNG step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-png/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter WORKBOOK vers PNG à partir de Excel" h2="Bibliothèque NodeJS pour exporter WORKBOOK vers le fichier PNG" p="Utilisez Export API de Cells Cloud pour exporter les workflows d\'objets internes du fichier Excel dans NodeJS. Il s\'agit d\'une solution professionnelle pour exporter un WORKBOOK au format PNG à partir d\'une feuille de calcul en ligne à l\'aide de NodeJS." urlsection="export/workbook-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporter l\'objet WORKBOOK vers un fichier au format PNG à l\'aide du SDK Cloud Cells pour NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet WORKBOOK vers le fichier PNG à partir du fichier Excel est une tâche complexe. Les transitions d'exportation du format WORKBOOK vers PNG sont effectuées par notre SDK NodeJS tout en conservant le contenu structurel et logique principal de la feuille de calcul WORKBOOK source. Notre bibliothèque NodeJS est une solution professionnelle pour exporter des objets WORKBOOK vers des fichiers au format PNG en ligne. Ce SDK Cloud offre aux développeurs NodeJS des fonctionnalités puissantes et une sortie PNG parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans NodeJS utilisant REST API pour exporter WORKBOOK au format PNG à partir d\'une feuille de calcul" gistPath="" %}}
  
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
      format: "png",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Node pour exporter des objets de Excel WORKBOOK vers PNG" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `postExport` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>nœud v6.17.1 ou version ultérieure</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
