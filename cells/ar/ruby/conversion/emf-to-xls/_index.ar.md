---
title:  EMF إلى XLS تحويل API لروبي
description:  استخدام Aspose.Cells Cloud SDK لـ Ruby لتحويل ملف تنسيق EMF إلى ملف بتنسيق XLS.
url: /ar/ruby/conversion/emf-to-xls/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="روبي API لتحويل EMF إلى XLS" h2="مكتبة روبي لتحويل EMF إلى XLS" p="استخدم Cells Conversion REST API لإنشاء مسارات عمل جدول بيانات مخصصة في Ruby. هذا حل احترافي لتحويل EMF إلى XLS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Ruby." urlsection="conversion/emf-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف EMF إلى XLS في Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من EMF إلى XLS مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق EMF إلى XLS بواسطة Ruby SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات EMF المصدر. تعد مكتبة Ruby الخاصة بنا حلاً احترافيًا لتحويل EMF إلى ملفات XLS عبر الإنترنت. يمنح Cloud SDK مطوري Ruby وظائف قوية وإخراج XLS مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال التعليمات البرمجية في Ruby باستخدام REST API لتحويل EMF إلى تنسيق XLS" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.emf"
            format = 'xls'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام روبي API لتحويل EMF إلى XLS" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>خلايا الاتصال_دفتر العمل_يضع_يتحول_طريقة المصنف للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>روبي 2.5 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
