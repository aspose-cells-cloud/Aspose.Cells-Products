---
title:  Enregistrez MHTML au format SQL en utilisant Java
description: Utilisation du SDK Cloud Aspose.Cells for Java pour enregistrer le fichier au format MHTML en tant que fichier au format SQL.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer MHTML au format SQL" h2="Bibliothèque Java pour enregistrer MHTML au format SQL" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans Java. Il s\'agit d\'une solution professionnelle pour enregistrer du MHTML au format SQL et d\'autres formats de document en ligne à l\'aide de Java." urlsection="saveas/mhtml-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier MHTML au format SQL dans Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers MHTML au format SQL est une tâche complexe. Toutes les transitions du format MHTML vers SQL sont effectuées par notre SDK Java tout en conservant le contenu structurel et logique principal de la feuille de calcul MHTML source. Notre bibliothèque Java est une solution professionnelle pour enregistrer du MHTML sous forme de fichiers SQL en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et une sortie SQL parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Exemple de code pour enregistrer MHTML au format SQL à l\'aide de REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.mhtml";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.sql";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Cells Cloud SDK for Java pour enregistrer des fichiers Excel sous d\'autres formats MHTML comme SQL" >}}
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
