﻿---
title:  Enregistrez XLTX sous EMF API for Java
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/java/saveas/xltx-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API pour enregistrer XLTX sous EMF" h2="Bibliothèque Java pour enregistrer XLTX sous EMF" p="Utilisez Cells SaveAs REST API pour créer des flux de travail de feuille de calcul personnalisés dans Java. Il s\'agit d\'une solution professionnelle pour enregistrer XLTX sous EMF et d\'autres formats de documents en ligne à l\'aide de Java." urlsection="saveas/xltx-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier XLTX sous EMF dans Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers à partir de XLTX sous le nom EMF est une tâche complexe. Toutes les transitions de format XLTX vers EMF sont effectuées par notre SDK Java tout en conservant le contenu structurel et logique principal de la feuille de calcul XLTX source. Notre bibliothèque Java est une solution professionnelle pour enregistrer des fichiers XLTX sous EMF en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et une sortie EMF parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Java utilisant REST API pour enregistrer XLTX au format EMF" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xltx";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.emf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Java API pour enregistrer XLTX sous EMF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode cellsSaveAsPostDocumentSaveAs pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou plus récent</li>
<li>Java(TM) Environnement d'exécution SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}