---
title:  PHP'i kullanarak XLS'yi XLSM olarak kaydedin
description:  XLS formatındaki dosyayı XLSM formatındaki dosya olarak kaydetmek için PHP için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save XLS as XLSM, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLS as XLSM using the Cells Cloud PHP library.","description": "How to save XLS as XLSM using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/saveas/xls-to-xlsm/","step": [{ "@type": "HowToStep","name": "How to save XLS as XLSM using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xls-to-xlsm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLS as XLSM using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xls-to-xlsm/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLS as XLSM using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xls-to-xlsm/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to save XLS as XLSM using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xls-to-xlsm/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLS\'yi XLSM olarak kaydet" h2="XLS\'yi XLSM olarak kaydetmek için PHP kütüphane" p="PHP\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API\'i Kaydet\'i kullanın. Bu, PHP\'i kullanarak XLS\'yi XLSM ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xls-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Bir XLS dosyasını PHP\'e XLSM olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını XLS'den XLSM olarak kaydetmek karmaşık bir iştir. XLS'den XLSM'ye tüm format geçişleri PHP SDK'mız tarafından gerçekleştirilir ve kaynak XLS elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. PHP kitaplığımız, XLS'yi çevrimiçi XLSM dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, PHP geliştiriciye güçlü işlevsellik ve mükemmel XLSM çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP REST API kullanarak XLS\'yi XLSM olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xls';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "xlsm";
    $newfilename = "Book1Saveas.xlsm";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud PHP kitaplığını kullanarak XLS\'yi XLSM olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>PHP kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı PHP'de açın.</li>
<li>Ortaya çıkan akışı almak için `PostWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>PHP 7.4 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
