---
title:  Convertir XLT en XPS à l'aide de NodeJS
description:  Utilisation du SDK Cloud Aspose.Cells pour NodeJS pour convertir un fichier au format XLT en fichier au format XPS.
kwords: Excel, Convert XLT to XPS, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLT to XPS using the Cells Cloud NodeJS library.","description": "How to convert XLT to XPS using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/conversion/xlt-to-xps/","step": [{ "@type": "HowToStep","name": "How to convert XLT to XPS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xlt-to-xps/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLT to XPS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xlt-to-xps/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLT to XPS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xlt-to-xps/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to convert XLT to XPS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xlt-to-xps/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir XLT en XPS" h2="Bibliothèque NodeJS pour convertir XLT en XPS" p="Utilisez la conversion API du Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans les projets NodeJS. Il s\'agit d\'une solution professionnelle pour convertir XLT en XPS et d\'autres formats de documents en ligne à l\'aide de NodeJS." urlsection="conversion/xlt-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertir XLT en XPS à l\'aide du SDK Cloud Cells pour NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLT vers XPS peut être une tâche complexe. Notre SDK NodeJS gère toutes les conversions du format XLT vers XPS tout en préservant le contenu structurel et logique principal de la feuille de calcul XLT source. Notre bibliothèque NodeJS fournit une solution professionnelle pour convertir en ligne des fichiers XLT en XPS. Ce SDK Cloud offre aux développeurs NodeJS des fonctionnalités puissantes et garantit une sortie XPS de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code NodeJS pour convertir XLT en XPS à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xlt"),
        format: "xps",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment convertir XLT en XPS à l\'aide de la bibliothèque Cloud NodeJS Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque NodeJS et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en JavaScript.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>nœud v6.17.1 ou version ultérieure</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
