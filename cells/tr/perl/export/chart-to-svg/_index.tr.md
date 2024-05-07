---
title:  Perl için Cells Cloud SDK'yı kullanarak CHART'ı Excel'den SVG'e aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
kwords: Excel, chart, svg, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Perl to export objects from Excel CHART to SVG","description": "How to use Cells Cloud SDK for Perl to export objects from Excel CHART to SVG","image": {"@type": "ImageObject"},"url": "/perl/export/chart-to-svg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel CHART to SVG step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/chart-to-svg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel CHART to SVG step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/chart-to-svg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel CHART to SVG step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/chart-to-svg/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="CHART\'ı Excel\'den SVG\'e aktar" h2="CHART\'ı SVG dosyasına aktarmak için Perl kitaplığı" p="Perl\'de Excel dosya dahili nesne iş akışlarını dışa aktarmak için Cells Bulut\'un API\'ini Dışa Aktar\'ı kullanın. Bu, Perl\'i kullanarak çevrimiçi elektronik tablodan CHART\'ı SVG biçimindeki dosyaya dışa aktarmak için profesyonel bir çözümdür." urlsection="export/chart-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Perl için Cells Bulut SDK\'sını kullanarak CHART nesnesini SVG biçimindeki dosyaya aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
CHART nesnesini Excel dosyasından SVG dosyasına aktarmak karmaşık bir iştir. CHART'ı SVG'e aktarma format geçişleri Perl SDK'mız tarafından gerçekleştirilirken, kaynak CHART elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. Perl kitaplığımız, CHART nesnelerini çevrimiçi olarak SVG formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK, Perl geliştiriciye güçlü işlevsellik ve mükemmel SVG çıktı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="CHART\'ı elektronik tablodan SVG formatına aktarmak için REST API\'i kullanan Perl\'deki kod örneği" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'chart',format => 'svg');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Nesneleri Excel CHART\'tan SVG\'e dışa aktarmak için Perl için Cells Cloud SDK nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için post_export yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
