---
title:  Конвертировать из Excel FODS в XLSM via Рубин
description: Создавайте, редактируйте или конвертируйте файлы Excel с помощью REST API и Ruby SDK с открытым исходным кодом.
url: /ru/ruby/conversion/fods-to-xlsm/
family: cells
platformtag: ruby
feature: conversion
informat: FODS
outformat: XLSM
platform: Ruby
otherformats: XLSM XLTM ODS MHTML CSV XML PDF XLTX FODS DIF MD TIFF XPS XLSX TXT XLSB 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразование FODS в XLSM с помощью Ruby" h2="Чтение, редактирование и экспорт данных Excel в другие форматы с помощью Cloud SDK с открытым исходным кодом для Ruby." >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Преобразование FODS в XLSM с помощью Ruby" %}}
1.  Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API
1. Инициализируйте ```CellsApi```, используя идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.
1. Загрузите файл FODS в облачное хранилище по умолчанию с помощью метода ```CellsApi.upload_file```.
1. Вызовите метод ```CellsApi.cells_save_as_post_document_save_as```, чтобы получить результирующий файл XLSM.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начните с Excel API и Ruby SDK" %}}
Получите исходный код Cloud SDK для Ruby Excel на сайте[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby) скомпилировать SDK самостоятельно или перейти к[Релизы](https://releases.aspose.cloud/) альтернативные варианты загрузки.

 Также взгляните на Swagger на основе[API Ссылка](https://apireference.aspose.cloud/cells/) чтобы узнать больше о[Excel ОТДЫХ API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код Ruby для преобразования FODS в XLSM" gistPath="" %}}
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
    newfilename = 'output.xlsm'
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