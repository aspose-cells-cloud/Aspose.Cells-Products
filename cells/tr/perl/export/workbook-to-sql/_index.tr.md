---
title:  Perl için Cells Cloud SDK'yı kullanarak ÇALIŞMA KİTABI'nı Excel'den SQL'e aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="ÇALIŞMA KİTABI\'nı Excel\'den SQL\'e aktar" h2="Perl ÇALIŞMA KİTABI\'nı SQL dosyasına aktarmak için kütüphane" p="Perl\'de Excel dosya dahili nesne iş akışlarını dışa aktarmak için Cells Bulut\'un API\'ini Dışa Aktar\'ı kullanın. Bu, Perl\'i kullanarak çevrimiçi tablodan ÇALIŞMA KİTAPÇIĞINI SQL formatındaki dosyaya dışa aktarmak için profesyonel bir çözümdür." urlsection="export/workbook-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="Perl için Cells Cloud SDK\'yı kullanarak ÇALIŞMA KİTABI nesnesini SQL format dosyasına aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
WORKBOOK nesnesini Excel dosyasından SQL dosyasına aktarmak karmaşık bir iştir. ÇALIŞMA KİTABI'nı SQL'e aktarma format geçişleri Perl SDK'mız tarafından gerçekleştirilir ve aynı zamanda kaynak ÇALIŞMA KİTABI e-tablosunun ana yapısal ve mantıksal içeriği korunur. Perl kitaplığımız, ÇALIŞMA KİTABI nesnelerini çevrimiçi olarak SQL formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK'sı, Perl geliştiriciye güçlü işlevsellik ve mükemmel SQL çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Çalışma kitabını e-tablodan SQL formatına aktarmak için REST API\'i kullanan Perl\'deki kod örneği" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use MIME::Base64;
    use AsposeCellsCloud::LightCellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::LightCellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $filemap = { 'Book1.xlsx' => '~/TestData/Book1.xlsx', 'myDocument.xlsx' => ~/TestData/myDocument.xlsx'};
    my $result = $instance->post_export(file => $filemap , object_type => 'workbook',format => 'sql');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Nesneleri Excel WORKBOOK\'tan SQL\'e aktarmak için Perl için Cells Cloud SDK nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için post_export yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
