﻿---
title:  احفظ JPG كـ WMF API لـ Perl
description:  Cloud APIs & SDKs لـ Microsoft Excel & OpenOffice Calc. تحويل جدول البيانات إلى ملف تنسيق آخر.
url: /ar/perl/saveas/jpg-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API لحفظ JPG كـ WMF" h2="Perl مكتبة لحفظ JPG كـ WMF" p="استخدم Cells SaveAs REST API لإنشاء مهام سير عمل جداول بيانات مخصصة في Perl. هذا حل احترافي لحفظ JPG بتنسيق WMF وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Perl." urlsection="saveas/jpg-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف JPG كملف WMF في Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
حفظ تنسيقات الملفات من JPG لأن WMF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق JPG إلى WMF بواسطة Perl SDK مع الحفاظ على المحتوى البنيوي والمنطقي الرئيسي لجدول بيانات JPG المصدر. مكتبتنا Perl هي حل احترافي لحفظ JPG كملفات WMF عبر الإنترنت. يوفر Cloud SDK للمطورين Perl وظائف قوية وإخراج WMF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Perl باستخدام REST API لحفظ JPG كتنسيق WMF" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.jpg';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.wmf';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Perl API لحفظ JPG كملف WMF" >}}
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