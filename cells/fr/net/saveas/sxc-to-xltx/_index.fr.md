---
title: Enregistrez SXC sous XLTX API pour C#
description:  Utilisation de Aspose.Cells Cloud SDK pour C# pour enregistrer le fichier au format SXC en tant que fichier au format XLTX.
url: /fr/net/saveas/sxc-to-xltx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API pour enregistrer SXC en XLTX" h2="Bibliothèque C# pour enregistrer SXC en XLTX" p="Utilisez Cells SaveAs REST API pour créer des workflows de feuille de calcul personnalisés dans Net. Il s\'agit d\'une solution professionnelle pour enregistrer SXC au format XLTX et d\'autres formats de documents en ligne en utilisant C#." urlsection="saveas/sxc-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrer un fichier SXC sous XLTX dans C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers de SXC au format XLTX est une tâche complexe. Toutes les transitions de format SXC vers XLTX sont effectuées par notre SDK C# tout en conservant le contenu structurel et logique principal de la feuille de calcul SXC source. Notre bibliothèque C# est une solution professionnelle pour enregistrer en ligne des fichiers SXC au format XLTX. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et une sortie XLTX parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans C# utilisant REST API pour enregistrer SXC au format XLTX" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.sxc";
    string newfilename = "Book1SaveAs.xltx";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser C# API pour enregistrer SXC en XLTX" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode CellsSaveAsPostDocumentSaveAs pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>NET Framework 4.5.2 ou plus récent</li>
<li>Net Standard 2.0 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
