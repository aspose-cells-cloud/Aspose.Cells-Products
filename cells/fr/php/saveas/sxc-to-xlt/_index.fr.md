---
title:  Enregistrez SXC au format XLT en utilisant PHP
description:  Utilisation du SDK Cloud Aspose.Cells pour PHP pour enregistrer le fichier au format SXC au format XLT.
kwords: Excel, Save SXC as XLT, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save SXC as XLT using the Cells Cloud PHP library.","description": "How to save SXC as XLT using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/saveas/sxc-to-xlt/","step": [{ "@type": "HowToStep","name": "How to save SXC as XLT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/sxc-to-xlt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save SXC as XLT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/sxc-to-xlt/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save SXC as XLT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/sxc-to-xlt/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to save SXC as XLT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/sxc-to-xlt/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer SXC en tant que XLT" h2="Bibliothèque PHP pour enregistrer SXC au format XLT" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans PHP. Il s\'agit d\'une solution professionnelle pour enregistrer SXC au format XLT et d\'autres formats de document en ligne à l\'aide de PHP." urlsection="saveas/sxc-to-xlt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier SXC au format XLT dans PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de SXC au format XLT est une tâche complexe. Toutes les transitions du format SXC vers XLT sont effectuées par notre SDK PHP tout en conservant le contenu structurel et logique principal de la feuille de calcul SXC source. Notre bibliothèque PHP est une solution professionnelle pour enregistrer SXC sous forme de fichiers XLT en ligne. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et une sortie XLT parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Exemple de code pour enregistrer SXC au format XLT à l\'aide de REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.sxc';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "xlt";
    $newfilename = "Book1Saveas.xlt";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment enregistrer SXC au format XLT à l\'aide de la bibliothèque Cells Cloud PHP." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque PHP et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en PHP.</li>
<li>Utilisez la méthode `PostWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>PHP 7.4 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
