---
title:  PHP'i kullanarak XLSB'yi PNG'e dönüştürün
description:  XLSB biçimindeki bir dosyayı PNG biçimindeki bir dosyaya dönüştürmek için PHP için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Convert XLSB to PNG, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLSB to PNG using the Cells Cloud PHP library.","description": "How to convert XLSB to PNG using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/xlsb-to-png/","step": [{ "@type": "HowToStep","name": "How to convert XLSB to PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlsb-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLSB to PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlsb-to-png/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLSB to PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlsb-to-png/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert XLSB to PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlsb-to-png/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLSB\'yi PNG\'e dönüştür" h2="XLSB\'yi PNG\'e dönüştürmek için PHP kütüphanesi" p="PHP projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, PHP\'i kullanarak XLSB\'yi PNG\'e ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xlsb-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="PHP için Cells Cloud SDK\'yı kullanarak XLSB\'yi PNG\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLSB'den PNG'e dönüştürmek karmaşık bir iş olabilir. PHP SDK'mız, kaynak XLSB e-tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm XLSB'den PNG formatına dönüşümleri gerçekleştirir. PHP kitaplığımız, XLSB'yi çevrimiçi olarak PNG dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, PHP geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli PNG çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Cells Cloud SDK\'yı kullanarak XLSB\'yi PNG\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlsb';    
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud PHP kitaplığını kullanarak XLSB\'yi PNG\'e dönüştürme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>PHP kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı PHP'de açın.</li>
<li>Ortaya çıkan akışı almak için `putConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
