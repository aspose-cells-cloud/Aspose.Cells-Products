---
title:  PHP'i kullanarak HTML'i PDF'e dönüştürün
description:  HTML biçimindeki bir dosyayı PDF biçimindeki bir dosyaya dönüştürmek için PHP için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Convert HTML to PDF, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert HTML to PDF using the Cells Cloud PHP library.","description": "How to convert HTML to PDF using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/html-to-pdf/","step": [{ "@type": "HowToStep","name": "How to convert HTML to PDF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/html-to-pdf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert HTML to PDF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/html-to-pdf/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert HTML to PDF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/html-to-pdf/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert HTML to PDF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/html-to-pdf/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="HTML\'i PDF\'e dönüştür" h2="HTML\'i PDF\'e dönüştürmek için PHP kitaplığı" p="PHP projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, HTML\'i PDF\'e ve diğer belge formatlarını PHP\'i kullanarak çevrimiçi olarak dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/html-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="PHP için Cells Cloud SDK\'yı kullanarak HTML\'i PDF\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını HTML'den PDF'e dönüştürmek karmaşık bir iş olabilir. PHP SDK'mız, kaynak HTML elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken, HTML'den PDF'e tüm format dönüştürmelerini gerçekleştirir. PHP kitaplığımız, HTML dosyalarını çevrimiçi olarak PDF'e dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, PHP geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli PDF çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Cells Cloud SDK\'yı kullanarak HTML\'i PDF\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.html';    
    $format ='pdf';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.pdf", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud PHP kitaplığını kullanarak HTML\'i PDF\'e dönüştürme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>PHP kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı PHP'de açın.</li>
<li>Ortaya çıkan akışı almak için `putConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
