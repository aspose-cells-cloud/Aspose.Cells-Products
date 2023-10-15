---
title:  Excel FODS'yi XLTX via Ruby'ye dönüştür
description: REST API ve Açık Kaynak Ruby SDK ile Excel dosyalarını oluşturun, düzenleyin veya dönüştürün
url: /tr/ruby/conversion/fods-to-xltx/
family: cells
platformtag: ruby
feature: conversion
informat: FODS
outformat: XLTX
platform: Ruby
otherformats: DIF XPS MHTML CSV SVG XLS XLSX XLT TIFF PDF XLSM TXT MD FODS XLTX XML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Ruby ile FODS\'yi XLTX\'e dönüştürün" h2="Ruby için açık kaynaklı Cloud SDK ile Excel verilerini okuyun, düzenleyin ve diğer formatlara aktarın" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Ruby ile FODS\'den XLTX\'e Dönüşüm" %}}
1.  Şu adreste bir hesap oluşturun:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını
1. ```CellsApi```'i İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın
1. FODS dosyasını ```CellsApi.upload_file``` yöntemiyle varsayılan Cloud Storage'a yükleyin
1. Ortaya çıkan XLTX dosyasını almak için ```CellsApi.cells_save_as_post_document_save_as``` yöntemini çağırın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Excel API ve Ruby SDK\'yı Kullanmaya Başlayın" %}}
Ruby kaynak kodu için Excel Cloud SDK'yı şu adresten edinin:[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby) SDK'yı kendiniz derlemek veya[Salıverme](https://releases.aspose.cloud/) Alternatif indirme seçenekleri için.

 Ayrıca Swagger tabanlıya da bir göz atın[API Referans](https://apireference.aspose.cloud/cells/) hakkında daha fazla bilgi edinmek için[Excel DİNLENME API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="FODS\'den XLTX\'e Dönüşüm için Ruby Kodu" gistPath="" %}}
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby

require 'aspose_cells_cloud'

class Workbook
  include AsposeCellsCloud
  def initialize
    @instance =  AsposeCellsCloud::CellsApi.new($client_id, $client_secret, $api_version, $baseurl) 
  end
  
  # Convert document and save result to storage
  def post_document_save_as
    name = $BOOK1
    save_options = nil
    newfilename = 'output.xltx'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = $TEMPFOLDER
    result = @instance.upload_file( folder + "/" + name, ::File.open(File.expand_path("data/" + name), "r") {|io| io.read(io.size) })
    expect(result.uploaded.size).to  be > 0
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder + "/" + newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
  end
end

workbook = Workbook.new()
puts workbook.post_document_save_as
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}