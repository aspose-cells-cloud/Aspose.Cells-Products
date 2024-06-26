---
title: Convertissez FODS en EMF en utilisant C#
description:  Utilisation du SDK Cloud Aspose.Cells pour C# pour convertir un fichier au format FODS en fichier au format EMF.
kwords: Excel, Convert FODS to EMF, REST, C#
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert FODS to EMF using the Cells Cloud Net library.","description": "How to convert FODS to EMF using the Cells Cloud Net library.","image": {"@type": "ImageObject"},"url": "/net/conversion/fods-to-emf/","step": [{ "@type": "HowToStep","name": "How to convert FODS to EMF using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/fods-to-emf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert FODS to EMF using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/fods-to-emf/","text": "Install C# library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert FODS to EMF using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/fods-to-emf/","text": "Open the source file in C#",},{ "@type": "HowToStep","name": "How to convert FODS to EMF using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/fods-to-emf/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider "},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir FODS en EMF" h2="Bibliothèque C# pour convertir FODS en EMF" p="Utilisez la conversion API du Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans les projets Net. Il s\'agit d\'une solution professionnelle pour convertir FODS en EMF et d\'autres formats de documents en ligne en utilisant C#." urlsection="conversion/fods-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez FODS en EMF à l\'aide du SDK Cloud Cells pour C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de FODS en EMF peut être une tâche complexe. Notre SDK C# gère toutes les conversions du format FODS au format EMF tout en préservant le contenu structurel et logique principal de la feuille de calcul FODS source. Notre bibliothèque C# fournit une solution professionnelle pour convertir en ligne FODS en fichiers EMF. Ce SDK Cloud offre aux développeurs C# des fonctionnalités puissantes et garantit une sortie EMF de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Exemple de code pour convertir FODS en EMF à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.fods";
    string format = "emf";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.emf";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment convertir FODS en EMF à l\'aide de la bibliothèque Cloud Net Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque C# et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source dans C#</li>
<li>Utilisez la méthode `PutConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>NET Framework 4.5.2 ou version ultérieure</li>
<li>Net Standard 2.0 ou version ultérieure</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
