﻿---
title: XLSX en EMF Convertir API en C#
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/net/conversion/xlsx-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API pour convertir XLSX en EMF" h2="Bibliothèque C# pour convertir XLSX en EMF" p="Utilisez Cells Conversion REST API pour créer des workflows de feuille de calcul personnalisés dans Net. Il s\'agit d\'une solution professionnelle pour convertir XLSX en EMF et d\'autres formats de documents en ligne en utilisant C#." urlsection="conversion/xlsx-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier XLSX en EMF en C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLSX en EMF est une tâche complexe. Toutes les transitions de format XLSX vers EMF sont effectuées par notre SDK C# tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSX source. Notre bibliothèque C# est une solution professionnelle pour convertir en ligne des fichiers XLSX en EMF. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et une sortie EMF parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans C# utilisant REST API pour convertir XLSX au format EMF" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsx";
    string format = "emf";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.emf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser C# API pour convertir XLSX en EMF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode CellsWorkbookPutConvertWorkbook pour obtenir le flux résultant</li>
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