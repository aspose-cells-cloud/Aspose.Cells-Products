---
title:  Enregistrez FODS sous PNG en utilisant Java
description: Utilisation du SDK Cloud Aspose.Cells for Java pour enregistrer le fichier au format FODS au format PNG.
kwords: Excel, Save FODS as PNG, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as PNG using the Cells Cloud Java library.","description": "How to save FODS as PNG using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/fods-to-png/","step": [{ "@type": "HowToStep","name": "How to save FODS as PNG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/fods-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as PNG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/fods-to-png/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as PNG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/fods-to-png/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save FODS as PNG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/fods-to-png/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer FODS sous le numéro PNG" h2="Bibliothèque Java pour enregistrer FODS sous PNG" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Java. Il s\'agit d\'une solution professionnelle pour enregistrer les FODS sous PNG et d\'autres formats de documents en ligne à l\'aide de Java." urlsection="saveas/fods-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier FODS sous PNG dans Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de FODS sous le nom PNG est une tâche complexe. Toutes les transitions du format FODS vers PNG sont effectuées par notre SDK Java tout en conservant le contenu structurel et logique principal de la feuille de calcul FODS source. Notre bibliothèque Java est une solution professionnelle pour enregistrer les FODS sous forme de fichiers PNG en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et une sortie PNG parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Exemple de code pour enregistrer FODS sous PNG à l\'aide de REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.fods";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.png";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment enregistrer FODS sous le nom PNG à l\'aide de la bibliothèque Cells Cloud Java." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Java et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Java.</li>
<li>Utilisez la méthode `postWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
