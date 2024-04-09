---
title:  PHP için Cells Cloud SDK'yı kullanarak ÇALIŞMA SAYFASINI Excel'den DOCX'e aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="ÇALIŞMA SAYFASINI Excel\'den DOCX\'e aktar" h2="PHP WORKSHEET\'i DOCX dosyasına aktarmak için kütüphane" p="PHP\'de Excel dosya dahili nesne iş akışlarını dışa aktarmak için Cells Bulut\'un API\'ini Dışa Aktar\'ı kullanın. Bu, PHP\'i kullanarak çevrimiçi elektronik tablodan ÇALIŞMA SAYFASI\'nı DOCX formatındaki dosyaya dışa aktarmak için profesyonel bir çözümdür." urlsection="export/worksheet-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="PHP için Cells Cloud SDK\'yı kullanarak WORKSHEET nesnesini DOCX formatındaki dosyaya aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
WORKSHEET nesnesini Excel dosyasından DOCX dosyasına aktarmak karmaşık bir iştir. WORKSHEET'i DOCX'e aktarma format geçişleri PHP SDK'mız tarafından gerçekleştirilir ve kaynak WORKSHEET e-tablosunun ana yapısal ve mantıksal içeriği korunur. PHP kitaplığımız, ÇALIŞMA SAYFASI nesnelerini çevrimiçi olarak DOCX formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK'sı, PHP geliştiriciye güçlü işlevsellik ve mükemmel DOCX çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="WORKSHEET\'i e-tablodan DOCX formatına aktarmak için REST API\'i kullanan PHP\'deki kod örneği" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'worksheet', 'docx' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Nesneleri Excel WORKSHEET\'ten DOCX\'e aktarmak için PHP için Cells Cloud SDK nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `postExport` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
