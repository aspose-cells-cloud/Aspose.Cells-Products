﻿---
title:  XLT إلى WMF - تحويل API لروبي
description:  Cloud APIs & SDKs لـ Microsoft Excel & OpenOffice Calc. تحويل جدول البيانات إلى ملف تنسيق آخر.
url: /ar/ruby/conversion/xlt-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API لتحويل XLT إلى WMF" h2="مكتبة روبي لتحويل XLT إلى WMF" p="استخدم Cells Conversion REST API لإنشاء مسارات عمل جدول بيانات مخصصة في Ruby. هذا حل احترافي لتحويل XLT إلى WMF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Ruby." urlsection="conversion/xlt-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف XLT إلى WMF في Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من XLT إلى WMF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XLT إلى WMF بواسطة Ruby SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات XLT المصدر. مكتبة Ruby الخاصة بنا هي حل احترافي لتحويل ملفات XLT إلى WMF عبر الإنترنت. يمنح Cloud SDK مطوري Ruby وظائف قوية وإخراج WMF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Ruby باستخدام REST API لتحويل XLT إلى تنسيق WMF" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlt"
            format = 'wmf'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Ruby API لتحويل XLT إلى WMF" >}}
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