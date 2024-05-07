---
title:  Convertissez SXC en PNG en utilisant PHP
description:  Utilisation du SDK Cloud Aspose.Cells pour PHP pour convertir un fichier au format SXC en fichier au format PNG.
kwords: Excel, Convert SXC to PNG, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert SXC to PNG using the Cells Cloud PHP library.","description": "How to convert SXC to PNG using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/sxc-to-png/","step": [{ "@type": "HowToStep","name": "How to convert SXC to PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/sxc-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert SXC to PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/sxc-to-png/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert SXC to PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/sxc-to-png/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert SXC to PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/sxc-to-png/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir SXC en PNG" h2="Bibliothèque PHP pour convertir SXC en PNG" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets PHP. Il s\'agit d\'une solution professionnelle pour convertir SXC en PNG et d\'autres formats de documents en ligne en utilisant PHP." urlsection="conversion/sxc-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez SXC en PNG à l\'aide du SDK Cloud Cells pour PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de SXC vers PNG peut être une tâche complexe. Notre SDK PHP gère toutes les conversions du format SXC vers PNG tout en préservant le contenu structurel et logique principal de la feuille de calcul SXC source. Notre bibliothèque PHP fournit une solution professionnelle pour convertir en ligne des fichiers SXC en PNG. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et garantit une sortie PNG de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Exemple de code pour convertir SXC en PNG à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.sxc';    
    $format ='png';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.png", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment convertir SXC en PNG à l\'aide de la bibliothèque Cells Cloud PHP." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque PHP et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en PHP.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>PHP 7.4 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
