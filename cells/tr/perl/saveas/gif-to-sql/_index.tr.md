---
title:  Perl'i kullanarak GIF'i SQL olarak kaydedin
description:  GIF formatındaki dosyayı SQL formatındaki dosya olarak kaydetmek için Perl için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save GIF as SQL, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save GIF as SQL using the Cells Cloud Perl library.","description": "How to save GIF as SQL using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/saveas/gif-to-sql/","step": [{ "@type": "HowToStep","name": "How to save GIF as SQL using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/gif-to-sql/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save GIF as SQL using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/gif-to-sql/","text": "Install Perl library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save GIF as SQL using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/gif-to-sql/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to save GIF as SQL using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/gif-to-sql/","text": "Call post_workbook_save_as method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="GIF\'i SQL olarak kaydet" h2="GIF\'i SQL olarak kaydetmek için Perl kitaplığı" p="Perl\'de özelleştirilmiş e-tablo iş akışları oluşturmak için SaveAs API / Cells Bulut\'u kullanın. Bu, Perl\'i kullanarak GIF\'i SQL ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/gif-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="Bir GIF dosyasını Perl\'de SQL olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını GIF'ten SQL olarak kaydetmek karmaşık bir iştir. Tüm GIF'den SQL'e format geçişleri Perl SDK'mız tarafından gerçekleştirilir ve kaynak GIF elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. Perl kitaplığımız, GIF'i çevrimiçi SQL dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Perl geliştiriciye güçlü işlevsellik ve mükemmel SQL çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl REST API kullanarak GIF\'i SQL olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.gif';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.sql';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Perl kitaplığını kullanarak GIF\'i SQL olarak kaydetme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Perl kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Perl'de açın.</li>
<li>Çağrı postası_çalışma kitabı_Ortaya çıkan akışı almak için save_as yöntemi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
