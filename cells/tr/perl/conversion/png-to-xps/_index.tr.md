---
title:  Perl'i kullanarak PNG'i XPS'e dönüştürün
description:  PNG biçimindeki bir dosyayı XPS biçimindeki bir dosyaya dönüştürmek için Perl için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Convert PNG to XPS, REST, Perl
howto: How to convert PNG to XPS using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="PNG\'i XPS\'e dönüştür" h2="PNG\'i XPS\'e dönüştürmek için Perl kitaplığı" p="Perl projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, PNG\'i XPS\'e ve diğer belge formatlarını Perl\'i kullanarak çevrimiçi olarak dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/png-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Perl için Cells Cloud SDK\'yı kullanarak PNG\'i XPS\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını PNG'den XPS'e dönüştürmek karmaşık bir iş olabilir. Perl SDK'mız, kaynak PNG elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken, PNG'den XPS'e tüm format dönüştürmelerini gerçekleştirir. Perl kitaplığımız, PNG dosyalarını çevrimiçi olarak XPS'e dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Perl geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli XPS çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Cells Cloud SDK\'yı kullanarak PNG\'i XPS\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xps";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.png");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.png") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xps") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Perl kitaplığını kullanarak PNG\'i XPS\'e nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Perl paketini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Perl'de açın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
