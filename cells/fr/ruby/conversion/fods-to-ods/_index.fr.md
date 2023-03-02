---
title:  Convertir de Excel FODS à ODS via Rubis
description: Créer, modifier ou convertir des fichiers Excel avec REST API et Open Source Ruby SDK
url: /fr/ruby/conversion/fods-to-ods/
family: cells
platformtag: ruby
feature: conversion
informat: FODS
outformat: ODS
platform: Ruby
otherformats: MD PDF XLSB XLTM FODS TIFF MHTML TXT SVG DIF XLTX XPS XLSM XML TSV CSV 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir FODS en ODS avec Ruby" h2="Lire, modifier et exporter des données Excel vers d\'autres formats avec le SDK Cloud open source pour Ruby" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion FODS en ODS avec Ruby" %}}
1.  Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API
1. Initialisez ```CellsApi``` avec l'ID client, le secret client, l'URL de base et la version API
1. Importer le fichier FODS dans Cloud Storage par défaut avec la méthode ```CellsApi.upload_file```
1. Appelez la méthode ```CellsApi.cells_save_as_post_document_save_as``` pour obtenir le fichier ODS résultant
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Démarrer avec Excel API et SDK Ruby" %}}
 Obtenez le code source Excel du SDK Cloud pour Ruby sur[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby) pour compiler le SDK vous-même ou dirigez-vous vers le[Communiqués](https://releases.aspose.cloud/) pour les options de téléchargement alternatives.

 Jetez également un œil à Swagger[API Référence](https://apireference.aspose.cloud/cells/) pour en savoir plus sur la[Excel REPOS API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Code Ruby pour la conversion FODS en ODS" gistPath="" %}}
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