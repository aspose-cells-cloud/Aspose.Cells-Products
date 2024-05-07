---
title:  Ruby kullanarak XLT'yi XML olarak kaydedin
description:  XLT formatındaki dosyayı XML formatındaki dosya olarak kaydetmek için Ruby için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save XLT as XML, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLT as XML using the Cells Cloud Ruby library.","description": "How to save XLT as XML using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/xlt-to-xml/","step": [{ "@type": "HowToStep","name": "How to save XLT as XML using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlt-to-xml/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLT as XML using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlt-to-xml/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLT as XML using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlt-to-xml/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save XLT as XML using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlt-to-xml/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLT\'yi XML olarak kaydet" h2="XLT\'yi XML olarak kaydetmek için Ruby kütüphanesi" p="Ruby\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API of Cells Cloud\'u kullanın. Bu, Ruby\'yi kullanarak XLT\'yi XML ve diğer belge formatlarında çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xlt-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section title="XLT dosyasını Ruby\'de XML olarak kaydetme" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını XLT'den XML olarak kaydetmek karmaşık bir iştir. Tüm XLT'den XML formatına geçişler Ruby SDK'mız tarafından gerçekleştirilir ve kaynak XLT elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. Ruby kitaplığımız, XLT'yi çevrimiçi XML dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Ruby geliştiricilerine güçlü işlevsellik ve mükemmel XML çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="REST API kullanarak XLT\'yi XML olarak kaydetmek için Ruby Kodu Örneği" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.xlt'
    save_options = nil
    newfilename = 'Book1Saveas.xml'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Ruby kitaplığını kullanarak XLT\'yi XML olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Ruby kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı Ruby'de açın.</li>
<li>Ortaya çıkan akışı almak için `post_workbook_save_as` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>yakut 2.5 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
