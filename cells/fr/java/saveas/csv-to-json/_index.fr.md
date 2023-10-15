---
title:  Enregistrez CSV au format JSON en utilisant Java
description:  Utilisation du SDK Cloud Aspose.Cells for Java pour enregistrer le fichier au format CSV au format JSON.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer CSV au format JSON" h2="Bibliothèque Java pour enregistrer CSV au format JSON" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Java. Il s\'agit d\'une solution professionnelle pour enregistrer CSV au format JSON et d\'autres formats de documents en ligne à l\'aide de Java." urlsection="saveas/csv-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier CSV au format JSON dans Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers CSV au format JSON est une tâche complexe. Toutes les transitions du format CSV vers JSON sont effectuées par notre SDK Java tout en conservant le contenu structurel et logique principal de la feuille de calcul CSV source. Notre bibliothèque Java est une solution professionnelle pour enregistrer des fichiers CSV sous forme de fichiers JSON en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et une sortie JSON parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Exemple de code pour enregistrer un fichier CSV au format JSON à l\'aide de REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.csv";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.json";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells for Java pour enregistrer les fichiers Excel sous d\'autres formats CSV comme JSON" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `postWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
