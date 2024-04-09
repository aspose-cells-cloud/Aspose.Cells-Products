---
title:  Ruby kullanarak NUMBERS'ı XLSB'ye dönüştürün
description:  NUMBERS biçimindeki bir dosyayı XLSB biçimindeki dosyaya dönüştürmek için Ruby için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert NUMBERS to XLSB, REST, Ruby
howto: How to convert NUMBERS to XLSB using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="NUMBERS\'i XLSB\'ye dönüştür" h2="NUMBERS\'ı XLSB\'ye dönüştürmek için Ruby kütüphanesi" p="Ruby projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Cloud\'un API Dönüşümünü kullanın. Bu, Ruby\'yi kullanarak NUMBERS\'ı XLSB\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/numbers-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Ruby için Cells Cloud SDK\'yı kullanarak NUMBERS\'ı XLSB\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını NUMBERS'tan XLSB'ye dönüştürmek karmaşık bir iş olabilir. Ruby SDK'mız, kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriğini korurken tüm NUMBERS'tan XLSB formatına dönüşümleri gerçekleştirir. Ruby kitaplığımız, NUMBERS dosyalarını çevrimiçi olarak XLSB dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, Ruby geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli XLSB çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Cells Cloud SDK\'yı kullanarak NUMBERS\'ı XLSB\'ye dönüştürmek için Ruby Kodu Örneği" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.numbers"
            format = 'xlsb'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Ruby kitaplığını kullanarak NUMBERS\'ı XLSB\'ye nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Ruby kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı Ruby'de açın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>yakut 2.5 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
