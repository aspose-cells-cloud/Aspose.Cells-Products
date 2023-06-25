---
title:  قم بتصدير SHAPE إلى SVG من جدول البيانات باستخدام Ruby API
description:  Aspose.Cells Cloud REST API يدعم تصدير {0} إلى {1} تنسيق الملفات باستخدام {2}.
url: /ar/ruby/export/shape-to-svg/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API لتصدير SHAPE إلى ملف SVG" h2="مكتبة روبي لتصدير الشكل إلى ملف SVG" p="استخدم Cells Export REST API لتصدير مسارات عمل العناصر الداخلية لجدول البيانات في Ruby. هذا حل احترافي لتصدير SHAPE إلى ملف بتنسيق SVG من جدول البيانات عبر الإنترنت باستخدام Ruby." urlsection="export/shape-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن SHAPE إلى ملف بتنسيق SVG في Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن SHAPE إلى ملف SVG من جدول البيانات مهمة معقدة. يتم تنفيذ انتقالات تنسيق تصدير SHAPE إلى SVG بواسطة Ruby SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات SHAPE. تعد مكتبة Ruby الخاصة بنا حلاً احترافيًا لتصدير كائنات SHAPE إلى ملفات بتنسيق SVG عبر الإنترنت. يمنح Cloud SDK مطوري Ruby وظائف قوية وإخراج SVG مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال التعليمات البرمجية في Ruby باستخدام REST API لتصدير SHAPE إلى تنسيق SVG من جدول البيانات" gistPath="" %}}
  
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
            format = 'svg'
            objectType =  'shape'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام روبي API لتصدير الشكل إلى SVG" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>اتصل بطريقة post_export للحصول على التدفق الناتج </li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>روبي 2.5 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
