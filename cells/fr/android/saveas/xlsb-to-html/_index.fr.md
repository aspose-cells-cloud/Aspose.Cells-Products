﻿---
title:  Enregistrer XLSB sous HTML en utilisant Android
description:  Utilisation du SDK Cloud Aspose.Cells pour Android pour enregistrer le fichier au format XLSB au format HTML.
kwords: Excel, Save XLSB as HTML, REST, Android
howto: How to save XLSB as HTML using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer XLSB sous le numéro HTML" h2="Bibliothèque Android pour enregistrer XLSB sous le nom HTML" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Android. Il s\'agit d\'une solution professionnelle pour enregistrer XLSB sous le numéro HTML et d\'autres formats de documents en ligne à l\'aide d\'Android." urlsection="saveas/xlsb-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier XLSB sous HTML dans Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers XLSB sous le nom HTML est une tâche complexe. Toutes les transitions du format XLSB vers HTML sont effectuées par notre SDK Android tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSB source. Notre bibliothèque Android est une solution professionnelle pour enregistrer XLSB en tant que fichiers HTML en ligne. Ce SDK Cloud offre aux développeurs Android des fonctionnalités puissantes et une sortie HTML parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code Android pour enregistrer XLSB sous HTML à l\'aide de REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xlsb";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.html";
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
