---
title:  PHP'i kullanarak BMP'i TIFF olarak kaydedin
description:  BMP format dosyasını TIFF format dosyası olarak kaydetmek için PHP için Aspose.Cells Cloud SDK'yı kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="BMP\'i TIFF olarak kaydet" h2="BMP\'i TIFF olarak kaydetmek için PHP kitaplığı" p="PHP\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API\'ini Kaydet\'i kullanın. Bu, BMP\'i TIFF olarak ve diğer belge formatlarını PHP\'i kullanarak çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/bmp-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="BMP dosyasını PHP\'e TIFF olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını BMP'den TIFF olarak kaydetmek karmaşık bir iştir. BMP ile TIFF arasındaki tüm format geçişleri, PHP SDK'mız tarafından gerçekleştirilir ve kaynak BMP elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. PHP kitaplığımız, BMP'i çevrimiçi olarak TIFF dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, PHP geliştiricilerine güçlü işlevsellik ve mükemmel TIFF çıktı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP REST API\'i kullanarak BMP\'i TIFF olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.bmp';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "tiff";
    $newfilename = "Book1Saveas.tiff";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer formatlar olarak kaydetmek için PHP için Cells Bulut SDK\'sı nasıl kullanılır? BMP, TIFF olarak" >}}
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
