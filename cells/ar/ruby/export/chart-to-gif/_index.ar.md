---
title:  قم بتصدير المخطط إلى GIF من جدول البيانات باستخدام Ruby API
description:  Aspose.Cells Cloud REST API يدعم تصدير ملف Excel وكائنات داخلية لأنواع ملفات النسق. SDK يدعم أنواع لغات التطوير. وهي تشمل Android و C# و Go و Java و NodeJS و Perl و PHP و Python و Ruby و swift.
url: /ar/ruby/export/chart-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API لتصدير المخطط إلى ملف GIF" h2="مكتبة Ruby لتصدير CHART إلى ملف GIF" p="استخدم Cells Export REST API لتصدير مسارات عمل العناصر الداخلية لجدول البيانات في Ruby. هذا حل احترافي لتصدير CHART إلى ملف بتنسيق GIF من جدول بيانات عبر الإنترنت باستخدام Ruby." urlsection="export/chart-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن المخطط إلى ملف بتنسيق GIF في روبي" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن CHART إلى ملف GIF من جدول البيانات مهمة معقدة. يتم إجراء انتقالات تصدير المخطط إلى تنسيق GIF بواسطة Ruby SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات CHART. تعد مكتبة Ruby الخاصة بنا حلاً احترافيًا لتصدير كائنات CHART إلى ملفات بتنسيق GIF عبر الإنترنت. يوفر Cloud SDK لمطوري Ruby وظائف قوية وإخراج GIF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Ruby باستخدام REST API لتصدير المخطط البياني إلى تنسيق GIF من جدول البيانات" gistPath="" %}}
  
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
            objectType =  'chart'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Ruby API لتصدير المخطط إلى GIF" >}}
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
