﻿---
title:  XLT'yi PHP için XLS API olarak kaydedin
description:  XLT biçim dosyasını XLS biçim dosyası olarak kaydetmek için PHP için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/php/saveas/xlt-to-xls/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLT\'yi XLS olarak kaydetmek için PHP API" h2="XLT\'yi XLS olarak kaydetmek için PHP kitaplığı" p="PHP\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, PHP\'i kullanarak XLT\'yi XLS ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xlt-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir XLT dosyasını PHP\'de XLS olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya biçimlerini XLT'den XLS olarak kaydetmek karmaşık bir görevdir. Tüm XLT'den XLS formatına geçişler, kaynak XLT e-tablosunun ana yapısal ve mantıksal içeriği korunurken PHP SDK'mız tarafından gerçekleştirilir. PHP kitaplığımız, XLT'yi çevrimiçi olarak XLS dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Cloud SDK, PHP geliştiricilerine güçlü işlevsellik ve mükemmel XLS çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="XLT\'yi XLS formatı olarak kaydetmek için REST API\'i kullanan PHP\'deki kod örneği" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlt';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "xls";
    $newfilename = "Book1Saveas.xls";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="XLT\'yi XLS olarak kaydetmek için PHP API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için cellSaveAsPostDocumentSaveAs yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}