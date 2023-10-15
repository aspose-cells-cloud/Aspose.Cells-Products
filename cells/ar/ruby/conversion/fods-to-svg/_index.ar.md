---
title:  تحويل من Excel فودس إلى SVG via روبي
description: إنشاء أو تحرير أو تحويل ملفات Excel باستخدام REST API وRuby SDK مفتوح المصدر
url: /ar/ruby/conversion/fods-to-svg/
family: cells
platformtag: ruby
feature: conversion
informat: FODS
outformat: SVG
platform: Ruby
otherformats: XLTX XLSB DIF XLSX TSV XPS HTML MHTML FODS XLTM TIFF XLSM CSV XML PDF MD 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل FODS إلى SVG مع روبي" h2="قراءة وتحرير وتصدير بيانات Excel إلى تنسيقات أخرى باستخدام Cloud SDK مفتوح المصدر لـ Ruby" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS إلى SVG التحويل مع روبي" %}}
1.  قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا
1. تهيئة ```CellsApi``` بمعرف العميل وسر العميل وعنوان URL الأساسي وإصدار API
1. قم بتحميل ملف FODS إلى التخزين السحابي الافتراضي بطريقة ```CellsApi.upload_file```
1. اتصل بطريقة ```CellsApi.cells_save_as_post_document_save_as``` لتحصل على الملف SVG الناتج
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ابدأ مع Excel API وRuby SDK" %}}
احصل على Excel Cloud SDK لكود مصدر Ruby من[جيثب](https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby) لتجميع SDK بنفسك أو التوجه إلى ملف[إطلاق](https://releases.aspose.cloud/) للحصول على خيارات التنزيل البديلة.

 قم أيضًا بإلقاء نظرة على المستندة إلى Swagger[API مرجع](https://apireference.aspose.cloud/cells/) لمعرفة المزيد عن[Excel الراحة API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="كود روبي لتحويل FODS إلى SVG" gistPath="" %}}
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
    newfilename = 'output.svg'
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