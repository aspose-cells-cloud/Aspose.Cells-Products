---
title:  Ruby kullanarak FODS'yi PDF'e dönüştürün
description:  FODS formatındaki bir dosyayı PDF formatındaki bir dosyaya dönüştürmek için Ruby için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert FODS to PDF, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert FODS to PDF using the Cells Cloud Ruby library.","description": "How to convert FODS to PDF using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/conversion/fods-to-pdf/","step": [{ "@type": "HowToStep","name": "How to convert FODS to PDF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/fods-to-pdf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert FODS to PDF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/fods-to-pdf/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert FODS to PDF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/fods-to-pdf/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to convert FODS to PDF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/fods-to-pdf/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="FODS\'yi PDF\'e dönüştür" h2="FODS\'yi PDF\'e dönüştürmek için Ruby kütüphanesi" p="Ruby projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Cloud\'un API Dönüşümünü kullanın. Bu, Ruby\'yi kullanarak FODS\'yi PDF\'e ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/fods-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Ruby için Cells Cloud SDK\'yı kullanarak FODS\'yi PDF\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını FODS'den PDF'e dönüştürmek karmaşık bir iş olabilir. Ruby SDK'mız, kaynak FODS elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm FODS'den PDF formatına dönüşümleri gerçekleştirir. Ruby kütüphanemiz, FODS'yi çevrimiçi olarak PDF dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, Ruby geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli PDF çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Cells Cloud SDK\'yı kullanarak FODS\'yi PDF\'e dönüştürmek için Ruby Kodu Örneği" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.fods"
            format = 'pdf'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Ruby kitaplığını kullanarak FODS\'yi PDF\'e dönüştürme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Ruby kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı Ruby'de açın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>yakut 2.5 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
