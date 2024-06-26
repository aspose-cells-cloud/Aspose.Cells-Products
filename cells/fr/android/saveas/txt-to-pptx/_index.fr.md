﻿---
title:  Enregistrer TXT au format PPTX avec Android
description:  Utilisation du SDK Cloud Aspose.Cells pour Android pour enregistrer le fichier au format TXT au format PPTX.
kwords: Excel, Save TXT as PPTX, REST, Android
howto: How to save TXT as PPTX using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer TXT en tant que PPTX" h2="Bibliothèque Android pour enregistrer TXT au format PPTX" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Android. Il s\'agit d\'une solution professionnelle pour enregistrer TXT au format PPTX et d\'autres formats de documents en ligne à l\'aide d\'Android." urlsection="saveas/txt-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrer un fichier TXT au format PPTX sous Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers TXT au format PPTX est une tâche complexe. Toutes les transitions du format TXT vers PPTX sont effectuées par notre SDK Android tout en conservant le contenu structurel et logique principal de la feuille de calcul TXT source. Notre bibliothèque Android est une solution professionnelle pour enregistrer TXT sous forme de fichiers PPTX en ligne. Ce SDK Cloud offre aux développeurs Android des fonctionnalités puissantes et une sortie PPTX parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code Android pour enregistrer TXT au format PPTX à l\'aide de REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.txt";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.pptx";
    String folder ="CellsTests";
    try
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Android pour enregistrer les fichiers Excel sous d\'autres formats" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `postWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Android 7 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
