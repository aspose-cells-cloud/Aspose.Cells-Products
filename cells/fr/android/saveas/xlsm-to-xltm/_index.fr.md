---
title:  Enregistrer XLSM en tant que XLTM en utilisant Android
description: Utilisation du SDK Cloud Aspose.Cells pour Android pour enregistrer le fichier au format XLSM en tant que fichier au format XLTM.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer XLSM en tant que XLTM" h2="Bibliothèque Android pour enregistrer XLSM en tant que XLTM" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Android. Il s\'agit d\'une solution professionnelle pour enregistrer XLSM au format XLTM et d\'autres formats de documents en ligne à l\'aide d\'Android." urlsection="saveas/xlsm-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrer un fichier XLSM au format XLTM sous Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers XLSM au format XLTM est une tâche complexe. Toutes les transitions du format XLSM vers XLTM sont effectuées par notre SDK Android tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSM source. Notre bibliothèque Android est une solution professionnelle pour enregistrer XLSM sous forme de fichiers XLTM en ligne. Ce SDK Cloud offre aux développeurs Android des fonctionnalités puissantes et une sortie XLTM parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code Android pour enregistrer XLSM en tant que XLTM à l\'aide de REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xlsm";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xltm";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Android pour enregistrer des fichiers Excel sous d\'autres formats XLSM comme XLTM" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `postWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Android 7 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
