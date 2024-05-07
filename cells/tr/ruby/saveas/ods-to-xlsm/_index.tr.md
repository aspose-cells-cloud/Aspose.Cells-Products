---
title:  Ruby kullanarak ODS'yi XLSM olarak kaydedin
description:  ODS formatındaki dosyayı XLSM formatındaki dosya olarak kaydetmek için Ruby için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save ODS as XLSM, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save ODS as XLSM using the Cells Cloud Ruby library.","description": "How to save ODS as XLSM using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/ods-to-xlsm/","step": [{ "@type": "HowToStep","name": "How to save ODS as XLSM using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-xlsm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save ODS as XLSM using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-xlsm/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save ODS as XLSM using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-xlsm/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save ODS as XLSM using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/ods-to-xlsm/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="ODS\'yi XLSM olarak kaydet" h2="ODS\'yi XLSM olarak kaydetmek için Ruby kütüphanesi" p="Ruby\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API of Cells Cloud\'u kullanın. Bu, Ruby\'yi kullanarak ODS\'yi XLSM ve diğer belge formatlarında çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/ods-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Bir ODS dosyasını Ruby\'de XLSM olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını ODS'den XLSM olarak kaydetmek karmaşık bir iştir. Tüm ODS'den XLSM formatına geçişler, kaynak ODS elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken Ruby SDK'mız tarafından gerçekleştirilir. Ruby kitaplığımız, ODS'yi çevrimiçi XLSM dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Ruby geliştiricilerine güçlü işlevsellik ve mükemmel XLSM çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="REST API kullanarak ODS\'yi XLSM olarak kaydetmek için Ruby Kod Örneği" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.ods'
    save_options = nil
    newfilename = 'Book1Saveas.xlsm'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Ruby kitaplığını kullanarak ODS\'yi XLSM olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Ruby kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı Ruby'de açın.</li>
<li>Ortaya çıkan akışı almak için `post_workbook_save_as` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>yakut 2.5 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
