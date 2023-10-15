---
title:  تصدير SHAPE إلى GIF من Excel باستخدام Cells Cloud SDK لروبي
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تصدير SHAPE إلى GIF من Excel" h2="مكتبة روبي لتصدير SHAPE إلى ملف GIF" p="استخدم تصدير API من Cells Cloud لتصدير Excel سير عمل الكائن الداخلي في Ruby. يعد هذا حلاً احترافيًا لتصدير ملف بتنسيق SHAPE إلى GIF من جدول البيانات عبر الإنترنت باستخدام Ruby." urlsection="export/shape-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتصدير كائن SHAPE إلى ملف بتنسيق GIF باستخدام Cells Cloud SDK لـ Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن SHAPE إلى ملف GIF من ملف Excel مهمة معقدة. يتم تنفيذ انتقالات تنسيق تصدير SHAPE إلى GIF بواسطة Ruby SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات SHAPE المصدر. تعد مكتبة Ruby الخاصة بنا حلاً احترافيًا لتصدير كائنات SHAPE إلى ملفات بتنسيق GIF عبر الإنترنت. يوفر Cloud SDK لمطوري Ruby وظائف قوية ومخرجات GIF مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال التعليمات البرمجية في روبي باستخدام REST API لتصدير SHAPE إلى تنسيق GIF من جدول البيانات" gistPath="" %}}
  
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
            format = 'gif'
            objectType =  'shape'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لروبي لتصدير الكائنات من Excel SHAPE إلى GIF" >}}
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
