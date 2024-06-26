---
title:  Enregistrez ODS au format XLT en utilisant Java
description:  Utilisation du SDK Cloud Aspose.Cells for Java pour enregistrer le fichier au format ODS au format XLT.
kwords: Excel, Save ODS as XLT, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save ODS as XLT using the Cells Cloud Java library.","description": "How to save ODS as XLT using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/ods-to-xlt/","step": [{ "@type": "HowToStep","name": "How to save ODS as XLT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/ods-to-xlt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save ODS as XLT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/ods-to-xlt/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save ODS as XLT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/ods-to-xlt/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save ODS as XLT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/ods-to-xlt/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer l\'ODS au format XLT" h2="Bibliothèque Java pour enregistrer ODS au format XLT" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Java. Il s\'agit d\'une solution professionnelle pour enregistrer l\'ODS au format XLT et d\'autres formats de document en ligne à l\'aide de Java." urlsection="saveas/ods-to-xlt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier ODS au format XLT dans Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers d'ODS au format XLT est une tâche complexe. Toutes les transitions du format ODS vers XLT sont effectuées par notre SDK Java tout en conservant le contenu structurel et logique principal de la feuille de calcul ODS source. Notre bibliothèque Java est une solution professionnelle pour enregistrer les ODS sous forme de fichiers XLT en ligne. Ce SDK Cloud offre aux développeurs Java des fonctionnalités puissantes et une sortie XLT parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Exemple de code pour enregistrer ODS au format XLT à l\'aide de REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.ods";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xlt";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment enregistrer ODS au format XLT à l\'aide de la bibliothèque Cells Cloud Java." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Java et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Java.</li>
<li>Utilisez la méthode `postWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Maven 2.2.0 ou version ultérieure</li>
<li>Environnement d'exécution Java(TM) SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
