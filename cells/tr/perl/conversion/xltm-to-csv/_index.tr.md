---
title:  Perl'i kullanarak XLTM'yi CSV'ye dönüştürün
description: XLTM biçimindeki bir dosyayı CSV biçimindeki bir dosyaya dönüştürmek için Perl için Aspose.Cells Bulut SDK'sını kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLTM\'yi CSV\'ye dönüştür" h2="XLTM\'yi CSV\'ye dönüştürmek için Perl kütüphane" p="Perl projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Perl numaralı telefonu kullanarak XLTM\'yi çevrimiçi olarak CSV\'ye ve diğer belge formatlarına dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xltm-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Perl için Cells Cloud SDK\'yı kullanarak XLTM\'yi CSV\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLTM'den CSV'ye dönüştürmek karmaşık bir iş olabilir. Perl SDK'mız, kaynak XLTM elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm XLTM'den CSV formatına dönüşümleri gerçekleştirir. Perl kitaplığımız, XLTM'yi çevrimiçi olarak CSV dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Perl geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli CSV çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Cells Cloud SDK\'yı kullanarak XLTM\'yi CSV\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "csv";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xltm");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xltm") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.csv") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="XLTM\'yi CSV\'ye dönüştürmek için Perl SDK nasıl kullanılır?" >}}
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
