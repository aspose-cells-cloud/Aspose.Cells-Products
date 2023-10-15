---
title:  Enregistrez TXT en tant qu'ODS en utilisant C#
description:  Utilisation du SDK Cloud Aspose.Cells pour C# pour enregistrer le fichier au format TXT en tant que fichier au format ODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer TXT en tant qu\'ODS" h2="Bibliothèque C# pour enregistrer TXT en tant qu\'ODS" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Net. Il s\'agit d\'une solution professionnelle pour enregistrer TXT au format ODS et autres formats de documents en ligne en utilisant le C#." urlsection="saveas/txt-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier TXT au format ODS dans C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de TXT en tant qu'ODS est une tâche complexe. Toutes les transitions du format TXT vers ODS sont effectuées par notre SDK C# tout en conservant le contenu structurel et logique principal de la feuille de calcul TXT source. Notre bibliothèque C# est une solution professionnelle pour enregistrer TXT sous forme de fichiers ODS en ligne. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et une sortie ODS parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Exemple de code pour enregistrer TXT en tant qu\'ODS à l\'aide de REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.txt";
    string newfilename = "Book1SaveAs.ods";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Net pour enregistrer les fichiers Excel sous d\'autres formats TXT comme ODS" >}}
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
