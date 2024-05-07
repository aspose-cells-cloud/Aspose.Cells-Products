---
title:  PHP için Cells Cloud SDK'yı kullanarak LISTOBJECT'i Excel'den SVG'e aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
kwords: Excel, listobject, svg, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to SVG","description": "How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to SVG","image": {"@type": "ImageObject"},"url": "/php/export/listobject-to-svg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to SVG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/listobject-to-svg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to SVG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/listobject-to-svg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to SVG step 1", "image": {"@type": "ImageObject",},"url": "/php/export/listobject-to-svg/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="LISTOBJECT\'i Excel\'den SVG\'e aktar" h2="LISTOBJECT\'i SVG dosyasına aktarmak için PHP kitaplığı" p="PHP\'de Excel dosya dahili nesne iş akışlarını dışa aktarmak için Cells Bulut\'un API\'ini Dışa Aktar\'ı kullanın. Bu, PHP\'i kullanarak çevrimiçi elektronik tablodan LISTOBJECT\'i SVG biçimli dosyaya dışa aktarmak için profesyonel bir çözümdür." urlsection="export/listobject-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="PHP için Cells Cloud SDK\'yı kullanarak LISTOBJECT nesnesini SVG biçimli dosyaya aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
LISTOBJECT nesnesini Excel dosyasından SVG dosyasına aktarmak karmaşık bir iştir. LISTOBJECT'i SVG'e aktarma format geçişleri PHP SDK'mız tarafından gerçekleştirilir ve kaynak LISTOBJECT elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. PHP kitaplığımız, LISTOBJECT nesnelerini çevrimiçi olarak SVG formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK, PHP geliştiriciye güçlü işlevsellik ve mükemmel SVG çıktı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="LISTOBJECT\'i e-tablodan SVG biçimine aktarmak için REST API\'i kullanan PHP\'deki kod örneği" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\LightCellsApi;
    $cells = new LightCellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $files = array (
        'DataSource' =>  "C:/datasource.xlsx",
        'AssemblyTest' => "C:/assemblytest.xlsx"
    );
    $result = $cells->postExport( $files,'listobject', 'svg' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Nesneleri Excel LISTOBJECT\'ten SVG\'e dışa aktarmak için PHP için Cells Bulut SDK\'sı nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `postExport` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
