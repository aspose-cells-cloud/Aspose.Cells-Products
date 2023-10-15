---
title:  تصدير المصنف إلى HTML من Excel باستخدام Cells Cloud SDK لروبي
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تصدير المصنف إلى HTML من Excel" h2="مكتبة روبي لتصدير المصنف إلى ملف HTML" p="استخدم تصدير API من Cells Cloud لتصدير Excel سير عمل الكائن الداخلي في Ruby. يعد هذا حلاً احترافيًا لتصدير WORKBOOK إلى ملف بتنسيق HTML من جدول البيانات عبر الإنترنت باستخدام Ruby." urlsection="export/workbook-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن WORKBOOK إلى ملف تنسيق HTML باستخدام Cells Cloud SDK لـ Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن WORKBOOK إلى ملف HTML من ملف Excel مهمة معقدة. يتم تنفيذ انتقالات تنسيق تصدير WORKBOOK إلى HTML بواسطة Ruby SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات WORKBOOK المصدر. تعد مكتبة Ruby الخاصة بنا حلاً احترافيًا لتصدير كائنات WORKBOOK إلى ملفات بتنسيق HTML عبر الإنترنت. يوفر Cloud SDK لمطوري Ruby وظائف قوية وإخراجًا مثاليًا HTML.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال للتعليمات البرمجية في روبي باستخدام REST API لتصدير المصنف إلى تنسيق HTML من جدول البيانات" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::LiteCellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            files = {}      
            name = $DataSourceXlsx
            files[name] = ::File.open(File.expand_path("data/"+name),"r") 
            name =$AssemblyTestXlsx 
            files[name] = ::File.open(File.expand_path("data/"+name),"r")
            format = 'html'
            objectType =  'workbook'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لروبي لتصدير الكائنات من المصنف Excel إلى HTML" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>قم باستدعاء طريقة post_export للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>روبي 2.5 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
