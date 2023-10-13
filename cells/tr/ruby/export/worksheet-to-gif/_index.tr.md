﻿---
title:  Ruby API kullanarak ÇALIŞMA TABLOSUNU e-tablodan GIF'e aktarın
description:  Aspose.Cells Cloud REST API, {0} dosyalarını {2} kullanarak {1} biçiminde dışa aktarmayı destekler.
url: /tr/ruby/export/worksheet-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="ÇALIŞMA TABLOSUNU GIF dosyasına dışa aktarmak için Ruby API" h2="ÇALIŞMA TABLOSUNU GIF dosyasına dışa aktarmak için Ruby kitaplığı" p="Ruby\'de elektronik tablo dahili nesne iş akışlarını dışa aktarmak için Cells Export REST API\'i kullanın. Bu, ÇALIŞMA TABLOSUNU Ruby kullanarak elektronik tablodan GIF formatındaki dosyaya aktarmak için profesyonel bir çözümdür." urlsection="export/worksheet-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="WORKSHEET nesnesini Ruby\'de GIF formatındaki dosyaya aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
WORKSHEET nesnesini e-tablodan GIF dosyasına aktarma karmaşık bir iştir. WORKSHEET'i GIF formatına aktarma geçişleri, kaynak WORKSHEET elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken Ruby SDK'mız tarafından gerçekleştirilir. Ruby kitaplığımız, WORKSHEET nesnelerini çevrimiçi olarak GIF formatındaki dosyalara dışa aktarmak için profesyonel bir çözümdür. Bu Cloud SDK, Ruby geliştiricilerine güçlü işlevsellik ve mükemmel GIF çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="WORKSHEET\'i e-tablodan GIF formatına dışa aktarmak için REST API kullanan Ruby\'deki kod örneği" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::LiteCellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            files = {}      
            name = $DataSourceXlsx
            files[name] = ::File.open(File.expand_path("data/"+name),"r") 
            name =$AssemblyTestXlsx 
            files[name] = ::File.open(File.expand_path("data/"+name),"r")
            format = 'gif'
            objectType =  'worksheet'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="WORKSHEET\'i GIF\'e dışa aktarmak için Ruby API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için post_export yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Yakut 2.5 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}