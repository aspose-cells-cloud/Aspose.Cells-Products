﻿---
title:  BMP'i XPS olarak kaydet Perl için API
description: BMP biçim dosyasını XPS biçim dosyası olarak kaydetmek için Perl için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/perl/saveas/bmp-to-xps/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="BMP\'i XPS olarak kaydetmek için Perl API" h2="BMP\'i XPS olarak kaydetmek için Perl kitaplığı" p="Perl\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, BMP\'i XPS olarak ve diğer belge biçimlerini Perl kullanarak çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/bmp-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir BMP dosyasını Perl\'de XPS olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
BMP'deki dosya biçimlerini XPS olarak kaydetmek karmaşık bir iştir. BMP'den XPS'e tüm biçim geçişleri, kaynak BMP e-tablosunun ana yapısal ve mantıksal içeriği korunurken Perl SDK'mız tarafından gerçekleştirilir. Perl kitaplığımız, BMP'i çevrimiçi olarak XPS dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Cloud SDK, Perl geliştiricilerine güçlü işlevsellik ve mükemmel XPS çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="BMP\'i XPS biçiminde kaydetmek için REST API\'i kullanan Perl\'deki kod örneği" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.bmp';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.xps';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="BMP\'i XPS olarak kaydetmek için Perl API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Çağrı hücreleri_kaydetmek_gibi_postalamak_belge_kaydetmek_sonuçtaki akışı alma yöntemi olarak</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}