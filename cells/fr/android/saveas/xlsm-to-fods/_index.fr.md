﻿---
title:  Enregistrer XLSM en tant que FODS en utilisant Android
description:  Utilisation du SDK Cloud Aspose.Cells pour Android pour enregistrer le fichier au format XLSM au format FODS.
kwords: Excel, Save XLSM as FODS, REST, Android
howto: How to save XLSM as FODS using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer XLSM en tant que FODS" h2="Bibliothèque Android pour enregistrer XLSM en tant que FODS" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Android. Il s\'agit d\'une solution professionnelle pour enregistrer XLSM au format FODS et autres formats de documents en ligne à l\'aide d\'Android." urlsection="saveas/xlsm-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrer un fichier XLSM au format FODS sous Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers XLSM au format FODS est une tâche complexe. Toutes les transitions du format XLSM vers FODS sont effectuées par notre SDK Android tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSM source. Notre bibliothèque Android est une solution professionnelle pour enregistrer XLSM sous forme de fichiers FODS en ligne. Ce SDK Cloud offre aux développeurs Android des fonctionnalités puissantes et une sortie FODS parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code Android pour enregistrer XLSM en tant que FODS à l\'aide de REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xlsm";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.fods";
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
