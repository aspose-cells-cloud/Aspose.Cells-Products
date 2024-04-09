---
title:  احفظ TSV بتنسيق XLSM باستخدام Ruby
description:  استخدام Aspose.Cells Cloud SDK لـ Ruby لحفظ ملف بتنسيق TSV كملف بتنسيق XLSM.
kwords: Excel, Save TSV as XLSM, REST, Ruby
howto: How to save TSV as XLSM using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ TSV بتنسيق XLSM" h2="مكتبة روبي لحفظ TSV بصيغة XLSM" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Ruby. يعد هذا حلاً احترافيًا لحفظ TSV بتنسيق XLSM وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Ruby." urlsection="saveas/tsv-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف TSV بتنسيق XLSM في Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من TSV بتنسيق XLSM مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق TSV إلى XLSM بواسطة Ruby SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات TSV المصدر. تعد مكتبة Ruby الخاصة بنا حلاً احترافيًا لحفظ TSV كملفات XLSM عبر الإنترنت. يوفر Cloud SDK لمطوري Ruby وظائف قوية ومخرجات XLSM مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على كود روبي لحفظ TSV كـ XLSM باستخدام REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.tsv'
    save_options = nil
    newfilename = 'Book1Saveas.xlsm'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية حفظ TSV بتنسيق XLSM باستخدام مكتبة Cloud Ruby Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة روبي وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في روبي.</li>
<li>استخدم طريقة `post_workbook_save_as` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>روبي 2.5 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
