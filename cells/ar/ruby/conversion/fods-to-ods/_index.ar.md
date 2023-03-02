---
title:  حوّل Excel FODS إلى ODS via Ruby
description: إنشاء ملفات Excel أو تحريرها أو تحويلها باستخدام REST API & Open Source Ruby SDK
url: /ar/ruby/conversion/fods-to-ods/
family: cells
platformtag: ruby
feature: conversion
informat: FODS
outformat: ODS
platform: Ruby
otherformats: MD PDF XLSB XLTM FODS TIFF MHTML TXT SVG DIF XLTX XPS XLSM XML TSV CSV 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل FODS إلى ODS باستخدام Ruby" h2="قراءة وتحرير وتصدير بيانات Excel إلى تنسيقات أخرى باستخدام Cloud SDK مفتوح المصدر لـ Ruby" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS لتحويل المواد المستنفدة للأوزون مع روبي" %}}
1.  قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية
1. قم بتهيئة ```CellsApi``` بمعرف العميل وسر العميل وعنوان URL الأساسي وإصدار API
1. قم بتحميل ملف FODS إلى التخزين السحابي الافتراضي باستخدام طريقة ```CellsApi.upload_file```
1. استدعاء طريقة ```CellsApi.cells_save_as_post_document_save_as``` للحصول على ملف ODS الناتج
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ابدأ مع Excel API و Ruby SDK" %}}
 احصل على Excel Cloud SDK للحصول على كود مصدر Ruby من[جيثب](https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby) لتجميع SDK بنفسك أو التوجه إلى ملف[إطلاق](https://releases.aspose.cloud/) للحصول على خيارات تنزيل بديلة.

 ألقِ نظرة أيضًا على Swagger المستندة إلى[API المرجع](https://apireference.aspose.cloud/cells/) لمعرفة المزيد عن[Excel راحة API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="كود روبي لتحويل FODS إلى ODS" gistPath="" %}}
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