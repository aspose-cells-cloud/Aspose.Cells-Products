﻿---
title:  Enregistrez PNG en tant que MHTML API pour Android
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/android/saveas/png-to-mhtml/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API pour enregistrer PNG en MHTML" h2="Bibliothèque Android pour enregistrer PNG en MHTML" p="Utilisez Cells SaveAs REST API pour créer des workflows de feuille de calcul personnalisés dans Android. Il s\'agit d\'une solution professionnelle pour enregistrer PNG au format MHTML et d\'autres formats de documents en ligne à l\'aide d\'Android." urlsection="saveas/png-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrer un fichier PNG au format MHTML dans Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers à partir de PNG en tant que MHTML est une tâche complexe. Toutes les transitions de format PNG vers MHTML sont effectuées par notre SDK Android tout en conservant le contenu structurel et logique principal de la feuille de calcul source PNG. Notre bibliothèque Android est une solution professionnelle pour enregistrer PNG sous forme de fichiers MHTML en ligne. Ce SDK Cloud offre aux développeurs Android des fonctionnalités puissantes et une sortie MHTML parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Android utilisant REST API pour enregistrer PNG au format MHTML" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.png";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.mhtml";
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
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Java API pour enregistrer PNG en MHTML" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode cellsSaveAsPostDocumentSaveAs pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Android 7 ou plus récent</li>
<li>Java(TM) Environnement d'exécution SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}