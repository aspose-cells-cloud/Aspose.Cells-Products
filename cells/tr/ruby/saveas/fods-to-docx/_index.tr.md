---
title:  Ruby kullanarak FODS'yi DOCX olarak kaydedin
description:  FODS formatındaki dosyayı DOCX formatındaki dosya olarak kaydetmek için Ruby için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save FODS as DOCX, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as DOCX using the Cells Cloud Ruby library.","description": "How to save FODS as DOCX using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/fods-to-docx/","step": [{ "@type": "HowToStep","name": "How to save FODS as DOCX using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/fods-to-docx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as DOCX using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/fods-to-docx/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as DOCX using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/fods-to-docx/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save FODS as DOCX using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/fods-to-docx/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="FODS\'yi DOCX olarak kaydet" h2="FODS\'yi DOCX olarak kaydetmek için Ruby kütüphanesi" p="Ruby\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API of Cells Cloud\'u kullanın. Bu, FODS\'yi DOCX ve diğer belge formatlarını Ruby kullanarak çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/fods-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Bir FODS dosyasını Ruby\'de DOCX olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını FODS'den DOCX olarak kaydetmek karmaşık bir iştir. Tüm FODS'den DOCX formatına geçişler, kaynak FODS elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken Ruby SDK'mız tarafından gerçekleştirilir. Ruby kütüphanemiz, FODS'yi çevrimiçi DOCX dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Ruby geliştiricilerine güçlü işlevsellik ve mükemmel DOCX çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="REST API kullanarak FODS\'yi DOCX olarak kaydetmek için Ruby Kod Örneği" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.fods'
    save_options = nil
    newfilename = 'Book1Saveas.docx'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Ruby kitaplığını kullanarak FODS\'yi DOCX olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Ruby kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı Ruby'de açın.</li>
<li>Ortaya çıkan akışı almak için `post_workbook_save_as` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>yakut 2.5 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
