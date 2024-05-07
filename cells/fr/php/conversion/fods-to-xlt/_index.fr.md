---
title:  Convertissez FODS en XLT en utilisant PHP
description:  Utilisation du SDK Cloud Aspose.Cells pour PHP pour convertir un fichier au format FODS en fichier au format XLT.
kwords: Excel, Convert FODS to XLT, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert FODS to XLT using the Cells Cloud PHP library.","description": "How to convert FODS to XLT using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/fods-to-xlt/","step": [{ "@type": "HowToStep","name": "How to convert FODS to XLT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/fods-to-xlt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert FODS to XLT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/fods-to-xlt/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert FODS to XLT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/fods-to-xlt/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert FODS to XLT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/fods-to-xlt/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir FODS en XLT" h2="Bibliothèque PHP pour convertir FODS en XLT" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets PHP. Il s\'agit d\'une solution professionnelle pour convertir FODS en XLT et d\'autres formats de documents en ligne en utilisant le PHP." urlsection="conversion/fods-to-xlt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez FODS en XLT à l\'aide du SDK Cloud Cells pour PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de FODS en XLT peut être une tâche complexe. Notre SDK PHP gère toutes les conversions du format FODS vers XLT tout en préservant le contenu structurel et logique principal de la feuille de calcul FODS source. Notre bibliothèque PHP fournit une solution professionnelle pour convertir en ligne des fichiers FODS en XLT. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et garantit une sortie XLT de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Exemple de code pour convertir FODS en XLT à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.fods';    
    $format ='xlt';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xlt", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment convertir FODS en XLT à l\'aide de la bibliothèque Cells Cloud PHP." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque PHP et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en PHP.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>PHP 7.4 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
