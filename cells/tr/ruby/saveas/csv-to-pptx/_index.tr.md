﻿---
title:  Ruby için CSV'yi PPTX API olarak kaydedin
description:  CSV formatındaki dosyayı PPTX formatındaki dosya olarak kaydetmek için Aspose.Cells Cloud SDK for Ruby kullanılıyor.
url: /tr/ruby/saveas/csv-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="CSV\'yi PPTX olarak kaydetmek için Ruby API" h2="CSV\'yi PPTX olarak kaydetmek için Ruby kitaplığı" p="Ruby\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, CSV\'yi Ruby kullanarak çevrimiçi olarak PPTX ve diğer belge biçimleri olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/csv-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir CSV dosyasını Ruby\'de PPTX olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya biçimlerini CSV'den PPTX olarak kaydetmek karmaşık bir iştir. Tüm CSV'den PPTX'e biçim geçişleri, kaynak CSV elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken Ruby SDK'mız tarafından gerçekleştirilir. Ruby kitaplığımız, CSV'yi çevrimiçi olarak PPTX dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Cloud SDK, Ruby geliştiricilerine güçlü işlevsellik ve mükemmel PPTX çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ruby\'de CSV\'yi PPTX formatı olarak kaydetmek için REST API kullanan kod örneği" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.csv'
    save_options = nil
    newfilename = 'Book1Saveas.pptx'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="CSV\'yi PPTX olarak kaydetmek için Ruby API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Çağrı hücreleri_kaydetmek_gibi_postalamak_belge_kaydetmek_sonuçtaki akışı alma yöntemi olarak</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Yakut 2.5 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}