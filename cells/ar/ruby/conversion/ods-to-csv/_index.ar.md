﻿---
title:  تحويل المواد المستنفدة للأوزون إلى CSV باستخدام روبي
description:  استخدام Aspose.Cells Cloud SDK لـ Ruby لتحويل ملف بتنسيق ODS إلى ملف بتنسيق CSV.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل المواد المستنفدة للأوزون إلى CSV" h2="مكتبة روبي لتحويل المواد المستنفدة للأوزون إلى CSV" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Ruby. يعد هذا حلاً احترافيًا لتحويل ODS إلى CSV وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Ruby." urlsection="conversion/ods-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ODS إلى CSV باستخدام Cells Cloud SDK لـ Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من ODS إلى CSV مهمة معقدة. يتعامل Ruby SDK الخاص بنا مع جميع تحويلات تنسيق ODS إلى CSV مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات ODS المصدر. توفر مكتبة Ruby الخاصة بنا حلاً احترافيًا لتحويل ملفات ODS إلى ملفات CSV عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Ruby من خلال وظائف قوية ويضمن إخراج CSV عالي الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على كود روبي لتحويل ODS إلى CSV باستخدام Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.ods"
            format = 'csv'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ Ruby لتحويل ملفات Excel إلى تنسيقات أخرى ODS إلى CSV" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `put_convert_workbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>روبي 2.5 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
