---
title: Ruby için Cells Cloud SDK'yı kullanarak RESİM'i Excel'den TIFF'e aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="RESMİ Excel\'den TIFF\'e aktar" h2="RESİM\'i TIFF dosyasına aktarmak için Ruby kütüphanesi" p="Ruby\'de Excel dosya dahili nesne iş akışlarını dışa aktarmak için Cells Cloud\'un API\'ini Dışa Aktar\'ı kullanın. Bu, Ruby kullanarak çevrimiçi elektronik tablodan RESİM\'i TIFF formatındaki dosyaya aktarmak için profesyonel bir çözümdür." urlsection="export/picture-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Ruby için Cells Cloud SDK\'yı kullanarak PICTURE nesnesini TIFF biçimindeki dosyaya aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
PICTURE nesnesini Excel dosyasından TIFF dosyasına aktarmak karmaşık bir iştir. PICTURE'ı TIFF'e aktar format geçişleri Ruby SDK'mız tarafından gerçekleştirilir ve kaynak PICTURE elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. Ruby kütüphanemiz, RESİM nesnelerini çevrimiçi olarak TIFF formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK, Ruby geliştiricilerine güçlü işlevsellik ve mükemmel TIFF çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ruby\'de REST API\'i kullanarak elektronik tablodan RESİM\'i TIFF formatına aktarmak için kod örneği" gistPath="" %}}
  
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
            format = 'tiff'
            objectType =  'picture'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel PICTURE\'dan TIFF\'e nesneleri dışa aktarmak için Ruby için Cells Cloud SDK nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için post_export yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>yakut 2.5 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
