﻿---
title:  Ruby için JPG'yi BMP'e API'e dönüştür
description:  JPG formatındaki dosyayı BMP formatındaki dosyaya dönüştürmek için Aspose.Cells Cloud SDK for Ruby'yi kullanma.
url: /tr/ruby/conversion/jpg-to-bmp/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="JPG\'yi BMP\'e dönüştürmek için Ruby API" h2="JPG\'yi BMP\'e dönüştürmek için Ruby kitaplığı" p="Ruby\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, JPG\'yi Ruby kullanarak çevrimiçi olarak BMP\'e ve diğer belge biçimlerine dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/jpg-to-bmp/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir JPG dosyasını Ruby\'de BMP\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını JPG'den BMP'e dönüştürmek karmaşık bir iştir. Tüm JPG'den BMP biçimine geçişler, kaynak JPG elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken Ruby SDK'mız tarafından gerçekleştirilir. Ruby kitaplığımız, JPG'yi çevrimiçi olarak BMP dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, Ruby geliştiricilerine güçlü işlevsellik ve mükemmel BMP çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ruby\'de JPG\'yi BMP biçimine dönüştürmek için REST API kullanan kod örneği" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.jpg"
            format = 'bmp'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="JPG\'yi BMP\'e dönüştürmek için Ruby API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Çağrı hücreleri_çalışma kitabı_koymak_dönüştürmek_sonuç akışını almak için çalışma kitabı yöntemi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Yakut 2.5 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}