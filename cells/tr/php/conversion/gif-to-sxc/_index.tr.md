﻿---
title:  GIF'i SXC'ye Dönüştür API için PHP
description:  GIF formatındaki dosyayı SXC formatındaki dosyaya dönüştürmek için Aspose.Cells Cloud SDK for PHP'i kullanma.
url: /tr/php/conversion/gif-to-sxc/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API GIF\'i SXC\'ye dönüştürmek için" h2="GIF\'i SXC\'ye dönüştürmek için PHP kitaplığı" p="PHP\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, PHP\'i kullanarak çevrimiçi olarak GIF\'i SXC\'ye ve diğer belge biçimlerine dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/gif-to-sxc/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="PHP\'de bir GIF dosyasını SXC\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya biçimlerini GIF'ten SXC'ye dönüştürmek karmaşık bir iştir. Tüm GIF'ten SXC formatına geçişler, kaynak GIF elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken PHP SDK'mız tarafından gerçekleştirilir. PHP kitaplığımız, GIF'i çevrimiçi olarak SXC dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, PHP geliştiricilerine güçlü işlevsellik ve mükemmel SXC çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="GIF\'i SXC formatına dönüştürmek için REST API\'i kullanan PHP\'deki kod örneği" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.gif';    
    $format ='sxc';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.sxc", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="GIF\'i SXC\'ye dönüştürmek için PHP API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için cellsWorkbookPutConvertWorkBook yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}