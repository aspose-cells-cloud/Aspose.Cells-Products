---
title:  Perl'i kullanarak XLSB'yi JPG'ye dönüştürün
description:  XLSB formatındaki bir dosyayı JPG formatındaki bir dosyaya dönüştürmek için Perl için Aspose.Cells Cloud SDK'yı kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSB\'yi JPG\'ye dönüştür" h2="XLSB\'yi JPG\'ye dönüştürmek için Perl kitaplığı" p="Perl projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Perl\'i kullanarak XLSB\'yi çevrimiçi olarak JPG\'ye ve diğer belge formatlarına dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xlsb-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Perl için Cells Cloud SDK\'yı kullanarak XLSB\'yi JPG\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLSB'den JPG'ye dönüştürmek karmaşık bir iş olabilir. Perl SDK'mız, kaynak XLSB e-tablosunun ana yapısal ve mantıksal içeriğini korurken tüm XLSB'den JPG formatına dönüşümleri gerçekleştirir. Perl kitaplığımız, XLSB'yi çevrimiçi olarak JPG dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, Perl geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli JPG çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Cells Bulut SDK\'yı kullanarak XLSB\'yi JPG\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "jpg";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xlsb");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xlsb") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.jpg") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="XLSB\'yi JPG\'ye dönüştürmek için Perl SDK nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
