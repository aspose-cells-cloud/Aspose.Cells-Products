---
title:  تحويل MHTML إلى SXC API لـ Perl
description:  استخدام Aspose.Cells Cloud SDK لـ Perl لتحويل ملف تنسيق MHTML إلى ملف بتنسيق SXC.
url: /ar/perl/conversion/mhtml-to-sxc/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API لتحويل MHTML إلى SXC" h2="Perl مكتبة لتحويل MHTML إلى SXC" p="استخدم Cells Conversion REST API لإنشاء جداول سير عمل مخصصة لجداول البيانات في Perl. هذا حل احترافي لتحويل MHTML إلى SXC وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Perl." urlsection="conversion/mhtml-to-sxc/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف MHTML إلى SXC في Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من MHTML إلى SXC مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق MHTML إلى SXC بواسطة Perl SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات MHTML المصدر. تعد مكتبتنا Perl حلاً احترافيًا لتحويل ملفات MHTML إلى SXC عبر الإنترنت. يوفر Cloud SDK للمطورين Perl وظائف قوية وإخراج SXC مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Perl باستخدام REST API لتحويل MHTML إلى تنسيق SXC" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "sxc";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.mhtml");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.mhtml") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.sxc") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Perl API لتحويل MHTML إلى SXC" >}}
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
