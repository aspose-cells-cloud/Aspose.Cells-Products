﻿---
title:  JPG إلى SVG حوّل API إلى Perl
description:  Cloud APIs & SDKs لـ Microsoft Excel & OpenOffice Calc. تحويل جدول البيانات إلى ملف تنسيق آخر.
url: /ar/perl/conversion/jpg-to-svg/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API لتحويل JPG إلى SVG" h2="مكتبة Perl لتحويل JPG إلى SVG" p="استخدم Cells Conversion REST API لإنشاء مهام سير عمل جداول بيانات مخصصة في Perl. هذا حل احترافي لتحويل JPG إلى SVG وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Perl." urlsection="conversion/jpg-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف JPG إلى SVG في Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من JPG إلى SVG مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق JPG إلى SVG بواسطة Perl SDK مع الحفاظ على المحتوى البنيوي والمنطقي الرئيسي لجدول بيانات JPG المصدر. تعد مكتبتنا Perl حلاً احترافيًا لتحويل ملفات JPG إلى ملفات SVG عبر الإنترنت. يوفر Cloud SDK للمطورين Perl وظائف قوية وإخراج SVG مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Perl باستخدام REST API لتحويل JPG إلى تنسيق SVG" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "svg";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.jpg");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.jpg") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.svg") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Perl API لتحويل JPG إلى SVG" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>خلايا الاتصال_دفتر العمل_يضع_يتحول_طريقة المصنف للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}