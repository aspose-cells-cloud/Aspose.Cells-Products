---
title:  Exportez la FEUILLE DE TRAVAIL vers XPS à partir de Excel à l'aide du SDK Cloud Cells pour C#.
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords: Excel, worksheet, xps, Net
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKSHEET to XPS","description": "How to use Cells Cloud SDK for Net to export objects from Excel WORKSHEET to XPS","image": {"@type": "ImageObject"},"url": "/net/export/worksheet-to-xps/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKSHEET to XPS step 1", "image": {"@type": "ImageObject",},"url": "/net/export/worksheet-to-xps/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKSHEET to XPS step 1", "image": {"@type": "ImageObject",},"url": "/net/export/worksheet-to-xps/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKSHEET to XPS step 1", "image": {"@type": "ImageObject",},"url": "/net/export/worksheet-to-xps/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider "},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter la FEUILLE DE TRAVAIL vers le XPS à partir du Excel" h2="Bibliothèque C# pour exporter WORKSHEET vers le fichier XPS" p="Utilisez Export API de Cells Cloud pour exporter les workflows d\'objets internes du fichier Excel dans Net. Il s\'agit d\'une solution professionnelle pour exporter une FEUILLE DE TRAVAIL au format XPS à partir d\'une feuille de calcul en ligne en utilisant C#." urlsection="export/worksheet-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportez l\'objet WORKSHEET vers un fichier au format XPS à l\'aide du SDK Cloud Cells pour C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet WORKSHEET vers le fichier XPS à partir du fichier Excel est une tâche complexe. Les transitions d’exportation de WORKSHEET au format XPS sont effectuées par notre SDK C# tout en conservant le contenu structurel et logique principal de la feuille de calcul WORKSHEET source. Notre bibliothèque C# est une solution professionnelle pour exporter en ligne des objets WORKSHEET vers des fichiers au format XPS. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et une sortie XPS parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans C# utilisant REST API pour exporter WORKSHEET au format XPS à partir d\'une feuille de calcul" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "xps";
    string objectType ="worksheet";
    LightCellsApi lightCellsApi =
        new LightCellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    IDictionary<string ,Stream> files = new  Dictionary<string ,Stream>();
    files.Add("Book1.xlsx" , File.OpenRead("Book1.xlsx"));
    files.Add("myDocument.xlsx", File.OpenRead("myDocument.xlsx"));
    var filesResult = lightCellsApi.PostExport(files, objectType, format);
    foreach (var file in filesResult.Files)
    {
        string v = file.FileContent;
        string filename = file.Filename;
        byte[] workbookData = System.Convert.FromBase64String(v);
        MemoryStream memoryStream = new MemoryStream(workbookData, 0, workbookData.Length);
        memoryStream.Seek(0, SeekOrigin.Begin);
        using (FileStream fileStream = File.Create( filename))
        {
            fileStream.Position = 0;
            memoryStream.CopyTo(fileStream);
            fileStream.Close();
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Cells Cloud SDK for Net pour exporter des objets de Excel WORKSHEET vers XPS" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `postExport` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>NET Framework 4.5.2 ou version ultérieure</li>
<li>Net Standard 2.0 ou version ultérieure</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
