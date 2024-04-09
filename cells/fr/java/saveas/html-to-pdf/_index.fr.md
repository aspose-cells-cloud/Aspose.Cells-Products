---
title:  Enregistrez HTML sous PDF en utilisant Java
description:  Utilisation du SDK Cloud Aspose.Cells for Java pour enregistrer le fichier au format HTML en tant que fichier au format PDF.
kwords: Excel, Save HTML as PDF, REST, Java
howto: How to save HTML as PDF using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer le HTML sous le nom PDF" h2="Bibliothèque Java pour enregistrer HTML sous le nom PDF" p="Utilisez SaveAs API de Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans Java. Il s\'agit d\'une solution professionnelle pour enregistrer HTML sous PDF et d\'autres formats de documents en ligne à l\'aide de Java." urlsection="saveas/html-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrer un fichier HTML sous PDF dans Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de HTML à PDF est une tâche complexe. Toutes les transitions de format HTML à PDF sont effectuées par notre SDK Java tout en conservant le contenu structurel et logique principal de la feuille de calcul source HTML. Notre bibliothèque Java est une solution professionnelle pour enregistrer HTML en tant que fichiers PDF en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et une sortie PDF parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Exemple de code pour enregistrer HTML sous PDF en utilisant REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.html";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.pdf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment enregistrer HTML sous PDF à l\'aide de la bibliothèque Cells Cloud Java." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Java et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Java.</li>
<li>Utilisez la méthode `postWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
