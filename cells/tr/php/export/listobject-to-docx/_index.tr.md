﻿---
title:  PHP API kullanarak LISTOBJECT'i elektronik tablodan DOCX'e aktarın
description:  Aspose.Cells Cloud REST API, {0} dosyalarını {2} kullanarak {1} biçiminde dışa aktarmayı destekler.
url: /tr/php/export/listobject-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="LISTOBJECT\'i DOCX dosyasına dışa aktarmak için PHP API" h2="LISTOBJECT\'i DOCX dosyasına dışa aktarmak için PHP kitaplığı" p="PHP\'deki e-tablo dahili nesne iş akışlarını dışa aktarmak için Cells Export REST API\'i kullanın. Bu, PHP kullanarak çevrimiçi elektronik tablodan LISTOBJECT\'i DOCX biçiminde dışa aktarmak için profesyonel bir çözümdür." urlsection="export/listobject-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="LISTOBJECT nesnesini PHP\'de DOCX biçim dosyasına aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
LISTOBJECT nesnesini elektronik tablodan DOCX dosyasına dışa aktarmak karmaşık bir iştir. LISTOBJECT'i DOCX biçimine dışa aktarma geçişleri, kaynak LISTOBJECT e-tablosunun ana yapısal ve mantıksal içeriği korunurken PHP SDK'mız tarafından gerçekleştirilir. PHP kitaplığımız, LISTOBJECT nesnelerini çevrimiçi olarak DOCX biçimindeki dosyalara dışa aktarmak için profesyonel bir çözümdür. Bu Cloud SDK, PHP geliştiricilerine güçlü işlevsellik ve mükemmel DOCX çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="LISTOBJECT\'i elektronik tablodan DOCX biçimine dışa aktarmak için REST API kullanan PHP\'deki kod örneği" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'listobject', 'docx' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="LISTOBJECT\'i DOCX\'e dışa aktarmak için PHP API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için postExport yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}