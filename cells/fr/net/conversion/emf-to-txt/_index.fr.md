﻿---
title:  EMF en TXT Convertir API pour C#
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/net/conversion/emf-to-txt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API pour convertir EMF en TXT" h2="bibliothèque C# pour convertir EMF en TXT" p="Utilisez Cells Conversion REST API pour créer des workflows de feuille de calcul personnalisés dans Net. Il s\'agit d\'une solution professionnelle pour convertir EMF en TXT et d\'autres formats de documents en ligne en utilisant C#." urlsection="conversion/emf-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier EMF en TXT en C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de EMF en TXT est une tâche complexe. Toutes les transitions du format EMF vers le format TXT sont effectuées par notre SDK C# tout en conservant le contenu structurel et logique principal de la feuille de calcul source EMF. Notre bibliothèque C# est une solution professionnelle pour convertir en ligne des fichiers EMF en fichiers TXT. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et une sortie TXT parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans C# utilisant REST API pour convertir EMF au format TXT" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.emf";
    string format = "txt";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.txt";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser C# API pour convertir EMF en TXT" >}}
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