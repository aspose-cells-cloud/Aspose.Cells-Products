---
title:  Convertissez XLTM en DOCX en utilisant C#
description: Utilisation du SDK Cloud Aspose.Cells pour C# pour convertir un fichier au format XLTM en fichier au format DOCX.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir XLTM en DOCX" h2="Bibliothèque C# pour convertir XLTM en DOCX" p="Utilisez la conversion API du Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans les projets Net. Il s\'agit d\'une solution professionnelle pour convertir XLTM en DOCX et d\'autres formats de documents en ligne en utilisant le C#." urlsection="conversion/xltm-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez XLTM en DOCX à l\'aide du SDK Cloud Cells pour C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLTM en DOCX peut être une tâche complexe. Notre SDK C# gère toutes les conversions du format XLTM vers DOCX tout en préservant le contenu structurel et logique principal de la feuille de calcul XLTM source. Notre bibliothèque C# fournit une solution professionnelle pour convertir des fichiers XLTM en fichiers DOCX en ligne. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et garantit une sortie DOCX de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Exemple de code pour convertir XLTM en DOCX à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xltm";
    string format = "docx";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.docx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Net pour convertir des fichiers Excel vers d\'autres formats XLTM en DOCX" >}}
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
