---
title:  تحويل JPG إلى ODS باستخدام Perl
description:  استخدام Aspose.Cells Cloud SDK لـ Perl لتحويل ملف بتنسيق JPG إلى ملف بتنسيق ODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل JPG إلى ODS" h2="مكتبة Perl لتحويل JPG إلى ODS" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Perl. يعد هذا حلاً احترافيًا لتحويل JPG إلى ODS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Perl." urlsection="conversion/jpg-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل JPG إلى ODS باستخدام Cells Cloud SDK لـ Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من JPG إلى ODS مهمة معقدة. يتعامل SDK Perl الخاص بنا مع جميع تحويلات تنسيق JPG إلى ODS مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات JPG المصدر. توفر مكتبتنا Perl حلاً احترافيًا لتحويل ملفات JPG إلى ملفات ODS عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Perl من الحصول على وظائف قوية ويضمن مخرجات ODS عالية الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl مثال على الكود لتحويل JPG إلى ODS باستخدام Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "ods";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.jpg");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.jpg") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.ods") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Perl SDK لتحويل JPG إلى ODS" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `put_convert_workbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
