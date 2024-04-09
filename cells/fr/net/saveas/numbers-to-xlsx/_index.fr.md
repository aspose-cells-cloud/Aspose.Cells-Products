---
title:  Enregistrez NUMBERS au format XLSX en utilisant C#
description:  Utilisation du SDK Cloud Aspose.Cells pour C# pour enregistrer le fichier au format NUMBERS au format XLSX.
kwords: Excel, Save NUMBERS as XLSX, REST, C#
howto: How to save NUMBERS as XLSX using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer NUMBERS au format XLSX" h2="Bibliothèque C# pour enregistrer des NUMBERS au format XLSX" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Net. Il s\'agit d\'une solution professionnelle pour enregistrer des NUMÉROS au format XLSX et d\'autres formats de documents en ligne en utilisant le C#." urlsection="saveas/numbers-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier NUMBERS au format XLSX dans C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de NUMBERS au format XLSX est une tâche complexe. Toutes les transitions du format NUMBERS vers XLSX sont effectuées par notre SDK C# tout en conservant le contenu structurel et logique principal de la feuille de calcul NUMBERS source. Notre bibliothèque C# est une solution professionnelle pour enregistrer des NUMBERS sous forme de fichiers XLSX en ligne. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et une sortie XLSX parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Exemple de code pour enregistrer NUMBERS au format XLSX à l\'aide de REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string newfilename = "Book1SaveAs.xlsx";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment enregistrer des NUMBERS au format XLSX à l\'aide de la bibliothèque Cloud Net Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque C# et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source dans C#</li>
<li>Utilisez la méthode `PostWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>NET Framework 4.5.2 ou version ultérieure</li>
<li>Net Standard 2.0 ou version ultérieure</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
