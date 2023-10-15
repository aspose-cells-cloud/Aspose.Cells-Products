---
title:  Convertir CSV en SVG en utilisant C#
description:  Utilisation du SDK Cloud Aspose.Cells pour C# pour convertir un fichier au format CSV en fichier au format SVG.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir CSV en SVG" h2="Bibliothèque C# pour convertir CSV en SVG" p="Utilisez la conversion API du Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans les projets Net. Il s\'agit d\'une solution professionnelle pour convertir CSV en SVG et d\'autres formats de documents en ligne en utilisant C#." urlsection="conversion/csv-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir CSV en SVG à l\'aide du SDK Cloud Cells pour C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers CSV en SVG peut être une tâche complexe. Notre SDK C# gère toutes les conversions du format CSV vers SVG tout en préservant le contenu structurel et logique principal de la feuille de calcul CSV source. Notre bibliothèque C# fournit une solution professionnelle pour convertir en ligne des fichiers CSV en fichiers SVG. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et garantit une sortie SVG de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Exemple de code pour convertir CSV en SVG à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.csv";
    string format = "svg";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.svg";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Cells Cloud SDK for Net pour convertir des fichiers Excel vers d\'autres formats CSV en SVG" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `PutConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>NET Framework 4.5.2 ou version ultérieure</li>
<li>Net Standard 2.0 ou version ultérieure</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
