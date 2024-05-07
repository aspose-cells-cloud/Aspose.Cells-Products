---
title:  PHP'i kullanarak XLTM'yi XLSX'e dönüştürün
description:  XLTM biçimindeki bir dosyayı XLSX biçimindeki dosyaya dönüştürmek için PHP için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Convert XLTM to XLSX, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLTM to XLSX using the Cells Cloud PHP library.","description": "How to convert XLTM to XLSX using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/xltm-to-xlsx/","step": [{ "@type": "HowToStep","name": "How to convert XLTM to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xltm-to-xlsx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLTM to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xltm-to-xlsx/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLTM to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xltm-to-xlsx/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert XLTM to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xltm-to-xlsx/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLTM\'yi XLSX\'ye dönüştür" h2="XLTM\'yi XLSX\'e dönüştürmek için PHP kütüphane" p="PHP projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, PHP numaralı telefonu kullanarak XLTM\'yi XLSX\'e ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xltm-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section title="PHP için Cells Cloud SDK\'yı kullanarak XLTM\'yi XLSX\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLTM'den XLSX'e dönüştürmek karmaşık bir iş olabilir. PHP SDK'mız, kaynak XLTM elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm XLTM'den XLSX formatına dönüşümleri gerçekleştirir. PHP kitaplığımız, XLTM'yi çevrimiçi olarak XLSX dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, PHP geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli XLSX çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Cells Bulut SDK\'yı kullanarak XLTM\'yi XLSX\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xltm';    
    $format ='xlsx';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xlsx", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud PHP kitaplığını kullanarak XLTM\'yi XLSX\'e dönüştürme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>PHP kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı PHP'de açın.</li>
<li>Ortaya çıkan akışı almak için `putConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
