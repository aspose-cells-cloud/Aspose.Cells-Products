﻿---
title:  احفظ TXT كـ PPTX API لـ Perl
description:  Cloud APIs & SDKs لـ Microsoft Excel & OpenOffice Calc. تحويل جدول البيانات إلى ملف تنسيق آخر.
url: /ar/perl/saveas/txt-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API لحفظ TXT كـ PPTX" h2="Perl مكتبة لحفظ TXT كـ PPTX" p="استخدم Cells SaveAs REST API لإنشاء مهام سير عمل جداول بيانات مخصصة في Perl. هذا حل احترافي لحفظ TXT كـ PPTX وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Perl." urlsection="saveas/txt-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف TXT بتنسيق PPTX في Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من TXT كـ PPTX مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق TXT إلى PPTX بواسطة Perl SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات TXT المصدر. تعتبر مكتبة Perl الخاصة بنا حلاً احترافيًا لحفظ TXT كملفات PPTX عبر الإنترنت. يوفر Cloud SDK للمطورين Perl وظائف قوية وإخراج PPTX مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Perl باستخدام REST API لحفظ TXT بتنسيق PPTX" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.txt';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.pptx';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Perl API لحفظ TXT كـ PPTX" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>خلايا الاتصال_يحفظ_مثل_بريد_وثيقة_يحفظ_كطريقة للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}