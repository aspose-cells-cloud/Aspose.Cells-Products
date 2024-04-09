---
title:  احفظ TXT كـ SVG باستخدام Ruby
description:  استخدام Aspose.Cells Cloud SDK لـ Ruby لحفظ ملف بتنسيق TXT كملف بتنسيق SVG.
kwords: Excel, Save TXT as SVG, REST, Ruby
howto: How to save TXT as SVG using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ TXT كـ SVG" h2="مكتبة روبي لحفظ TXT كـ SVG" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Ruby. يعد هذا حلاً احترافيًا لحفظ TXT بتنسيق SVG وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Ruby." urlsection="saveas/txt-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف TXT باسم SVG في روبي" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من TXT كـ SVG مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق TXT إلى SVG بواسطة Ruby SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات TXT المصدر. تعد مكتبة Ruby الخاصة بنا حلاً احترافيًا لحفظ TXT كملفات SVG عبر الإنترنت. يوفر Cloud SDK لمطوري Ruby وظائف قوية وإخراجًا مثاليًا SVG.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على كود روبي لحفظ TXT كـ SVG باستخدام REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.txt'
    save_options = nil
    newfilename = 'Book1Saveas.svg'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية حفظ TXT كـ SVG باستخدام مكتبة Cloud Ruby Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة روبي وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في روبي.</li>
<li>استخدم طريقة `post_workbook_save_as` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>روبي 2.5 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
