---
title:  PHP'i kullanarak XLTM'yi XPS olarak kaydedin
description:  XLTM formatındaki dosyayı XPS formatındaki dosya olarak kaydetmek için PHP için Aspose.Cells Cloud SDK'yı kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLTM\'yi XPS olarak kaydet" h2="XLTM\'yi XPS olarak kaydetmek için PHP kütüphanesi" p="PHP\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API\'ini Kaydet\'i kullanın. Bu, PHP\'i kullanarak XLTM\'yi XPS olarak ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xltm-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir XLTM dosyasını PHP\'e XPS olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını XLTM'den XPS olarak kaydetmek karmaşık bir iştir. XLTM'den XPS'e tüm format geçişleri, kaynak XLTM elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken PHP SDK'mız tarafından gerçekleştirilir. PHP kitaplığımız, XLTM'yi çevrimiçi olarak XPS dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, PHP geliştiricilerine güçlü işlevsellik ve mükemmel XPS çıktı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP XLTM\'yi REST API kullanarak XPS olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xltm';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "xps";
    $newfilename = "Book1Saveas.xps";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer XLTM formatlarında XPS olarak kaydetmek için PHP için Cells Bulut SDK\'sı nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `PostWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
