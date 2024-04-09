---
title:  Perl'i kullanarak CSV'yi ODS'ye dönüştürün
description: CSV formatındaki bir dosyayı ODS formatındaki dosyaya dönüştürmek için Perl için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert CSV to ODS, REST, Perl
howto: How to convert CSV to ODS using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="CSV\'yi ODS\'ye dönüştür" h2="CSV\'yi ODS\'ye dönüştürmek için Perl kitaplığı" p="Perl projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Perl\'i kullanarak CSV\'yi ODS\'ye ve diğer belge formatlarına çevrimiçi olarak dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/csv-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Perl için Cells Cloud SDK\'yı kullanarak CSV\'yi ODS\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını CSV'den ODS'ye dönüştürmek karmaşık bir iş olabilir. Perl SDK'mız, kaynak CSV e-tablosunun ana yapısal ve mantıksal içeriğini korurken tüm CSV'den ODS formatına dönüşümleri gerçekleştirir. Perl kitaplığımız, CSV'yi çevrimiçi olarak ODS dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Perl geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli ODS çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Cells Bulut SDK\'yı kullanarak CSV\'yi ODS\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "ods";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.csv");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.csv") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.ods") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Perl kitaplığını kullanarak CSV\'yi ODS\'ye nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Perl paketini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Perl'de açın.</li>
<li>Ortaya çıkan akışı almak için `put_convert_workbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
