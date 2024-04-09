---
title:  Exporter WORKBOOK vers MD à partir de Excel à l'aide du SDK Cloud Cells pour C#
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter WORKBOOK vers MD à partir du Excel" h2="Bibliothèque C# pour exporter WORKBOOK vers un fichier MD" p="Utilisez Export API de Cells Cloud pour exporter les workflows d\'objets internes du fichier Excel dans Net. Il s\'agit d\'une solution professionnelle pour exporter un WORKBOOK vers un fichier au format MD à partir d\'une feuille de calcul en ligne en utilisant le C#." urlsection="export/workbook-to-md/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportez l\'objet WORKBOOK vers un fichier au format MD à l\'aide du SDK Cloud Cells pour C#." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter un objet WORKBOOK vers un fichier MD à partir du fichier Excel est une tâche complexe. L'exportation des transitions au format WORKBOOK vers MD est effectuée par notre SDK C# tout en conservant le contenu structurel et logique principal de la feuille de calcul WORKBOOK source. Notre bibliothèque C# est une solution professionnelle pour exporter en ligne des objets WORKBOOK vers des fichiers au format MD. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et une sortie MD parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans C# utilisant REST API pour exporter WORKBOOK au format MD à partir d\'une feuille de calcul" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "md";
    string objectType ="workbook";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Cells Cloud SDK for Net pour exporter des objets de Excel WORKBOOK vers MD" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `postExport` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>NET Framework 4.5.2 ou version ultérieure</li>
<li>Net Standard 2.0 ou version ultérieure</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
