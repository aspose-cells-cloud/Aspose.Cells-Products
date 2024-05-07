---
title:  Perl'i kullanarak NUMBERS'ı JSON'a dönüştürün
description:  NUMBERS biçimindeki bir dosyayı JSON biçimindeki bir dosyaya dönüştürmek için Perl için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Convert NUMBERS to JSON, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert NUMBERS to JSON using the Cells Cloud Perl library.","description": "How to convert NUMBERS to JSON using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/conversion/numbers-to-json/","step": [{ "@type": "HowToStep","name": "How to convert NUMBERS to JSON using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/numbers-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert NUMBERS to JSON using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/numbers-to-json/","text": "Install Perl package and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to JSON using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/numbers-to-json/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to JSON using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/numbers-to-json/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="NUMBERS\'i JSON\'ye dönüştür" h2="NUMBERS\'ı JSON\'a dönüştürmek için Perl kitaplığı" p="Perl projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Perl\'i kullanarak NUMBERS\'ı JSON\'a ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/numbers-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Perl için Cells Cloud SDK\'yı kullanarak NUMBERS\'ı JSON\'a dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını NUMBERS'tan JSON'a dönüştürmek karmaşık bir iş olabilir. Perl SDK'mız, kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriğini korurken tüm NUMBERS'tan JSON formatına dönüşümleri gerçekleştirir. Perl kitaplığımız, NUMBERS'ı çevrimiçi olarak JSON dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Perl geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli JSON çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl NUMBERS\'ı Cells Cloud SDK kullanarak JSON\'a dönüştürmek için Kod Örneği" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "json";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.numbers");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.numbers") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.json") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Perl kitaplığını kullanarak NUMBERS\'ı JSON\'a dönüştürme." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Perl paketini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Perl'de açın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
