---
title:  Wandeln Sie von Excel FODS in ODS via Rubin um
description: Erstellen, bearbeiten oder konvertieren Sie Excel-Dateien mit REST API und Open Source Ruby SDK
url: /de/ruby/conversion/fods-to-ods/
family: cells
platformtag: ruby
feature: conversion
informat: FODS
outformat: ODS
platform: Ruby
otherformats: MD PDF XLSB XLTM FODS TIFF MHTML TXT SVG DIF XLTX XPS XLSM XML TSV CSV 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertieren Sie mit Ruby FODS in ODS" h2="Lesen, bearbeiten und exportieren Sie Excel-Daten in andere Formate mit Open Source Cloud SDK für Ruby" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS-zu-ODS-Konvertierung mit Ruby" %}}
1.  Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten
1. Initialisieren Sie ```CellsApi``` mit Client-ID, Client-Geheimnis, Basis-URL und API-Version
1. Laden Sie die FODS-Datei mit der Methode ```CellsApi.upload_file``` in den Standard-Cloud-Speicher hoch
1. Rufen Sie die Methode ```CellsApi.cells_save_as_post_document_save_as``` auf, um die resultierende ODS-Datei abzurufen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Beginnen Sie mit Excel API & Ruby SDK" %}}
 Holen Sie sich Excel Cloud SDK für Ruby-Quellcode von[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby) um das SDK selbst zu kompilieren oder gehen Sie zur[Freigaben](https://releases.aspose.cloud/) für alternative Download-Optionen.

 Schauen Sie sich auch Swagger-basiert an[API Referenz](https://apireference.aspose.cloud/cells/) um mehr über die zu erfahren[Excel RUHE API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Ruby-Code für die Konvertierung von FODS zu ODS" gistPath="" %}}
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
    newfilename = 'output.ods'
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