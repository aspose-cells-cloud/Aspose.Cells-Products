---
title:  Enregistrez EMF au format JPG en utilisant C#
description:  Utilisation du SDK Cloud Aspose.Cells pour C# pour enregistrer le fichier au format EMF au format JPG.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer EMF au format JPG" h2="Bibliothèque C# pour enregistrer EMF au format JPG" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Net. Il s\'agit d\'une solution professionnelle pour enregistrer EMF au format JPG et autres formats de documents en ligne en utilisant C#." urlsection="saveas/emf-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier EMF au format JPG dans C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers à partir de EMF au format JPG est une tâche complexe. Toutes les transitions du format EMF vers le format JPG sont effectuées par notre SDK C# tout en conservant le contenu structurel et logique principal de la feuille de calcul source EMF. Notre bibliothèque C# est une solution professionnelle pour enregistrer EMF sous forme de fichiers JPG en ligne. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et une sortie JPG parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Exemple de code pour enregistrer EMF au format JPG à l\'aide de REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.emf";
    string newfilename = "Book1SaveAs.jpg";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Net pour enregistrer les fichiers Excel sous d\'autres formats EMF au format JPG" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `PostWorkbookSaveAs` pour récupérer le flux résultant.</li>
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
