---
title:  PHP için Cells Cloud SDK'yı kullanarak ÇALIŞMA KİTABI'nı Excel'den TIFF'e aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="ÇALIŞMA KİTABINI Excel\'den TIFF\'e aktar" h2="ÇALIŞMA KİTABI\'nı TIFF dosyasına aktarmak için PHP kitaplığı" p="PHP\'de Excel dosya dahili nesne iş akışlarını dışa aktarmak için Cells Bulut\'un API\'ini Dışa Aktar\'ı kullanın. Bu, PHP\'i kullanarak çevrimiçi elektronik tablodan ÇALIŞMA KİTABI\'nı TIFF biçimindeki dosyaya dışa aktarmak için profesyonel bir çözümdür." urlsection="export/workbook-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="PHP için Cells Cloud SDK\'yı kullanarak ÇALIŞMA KİTABI nesnesini TIFF biçim dosyasına aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
ÇALIŞMA KİTABI nesnesini Excel dosyasından TIFF dosyasına aktarmak karmaşık bir iştir. ÇALIŞMA KİTABI'nı TIFF'e aktar format geçişleri PHP SDK'mız tarafından gerçekleştirilir ve kaynak ÇALIŞMA KİTABI e-tablosunun ana yapısal ve mantıksal içeriği korunur. PHP kitaplığımız, ÇALIŞMA KİTABI nesnelerini çevrimiçi olarak TIFF formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK, PHP geliştiriciye güçlü işlevsellik ve mükemmel TIFF çıktı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="ÇALIŞMA KİTABI\'nı e-tablodan TIFF biçimine aktarmak için REST API\'i kullanan PHP\'deki kod örneği" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'workbook', 'tiff' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Nesneleri Excel ÇALIŞMA KİTABI\'ndan TIFF\'e aktarmak için PHP için Cells Bulut SDK\'sı nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `postExport` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
