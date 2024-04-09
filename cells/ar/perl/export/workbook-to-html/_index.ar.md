---
title:  تصدير المصنف إلى HTML من Excel باستخدام Cells Cloud SDK لـ Perl
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="تصدير المصنف إلى HTML من Excel" h2="مكتبة Perl لتصدير المصنف إلى ملف HTML" p="استخدم تصدير API من Cells Cloud لتصدير سير عمل الكائن الداخلي للملف Excel في Perl. يعد هذا حلاً احترافيًا لتصدير المصنف إلى ملف بتنسيق HTML من جدول البيانات عبر الإنترنت باستخدام Perl." urlsection="export/workbook-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="تصدير كائن المصنف إلى ملف تنسيق HTML باستخدام Cells Cloud SDK لـ Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن WORKBOOK إلى ملف HTML من ملف Excel مهمة معقدة. يتم تنفيذ انتقالات تنسيق تصدير WORKBOOK إلى تنسيق HTML بواسطة Perl SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات WORKBOOK المصدر. تعد مكتبتنا Perl حلاً احترافيًا لتصدير كائنات المصنف إلى ملفات بتنسيق HTML عبر الإنترنت. يمنح Cloud SDK هذا مطوري Perl وظائف قوية وإخراج HTML مثاليًا.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على التعليمات البرمجية في Perl باستخدام REST API لتصدير المصنف إلى تنسيق HTML من جدول البيانات" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use MIME::Base64;
    use AsposeCellsCloud::LightCellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::LightCellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $filemap = { 'Book1.xlsx' => '~/TestData/Book1.xlsx', 'myDocument.xlsx' => ~/TestData/myDocument.xlsx'};
    my $result = $instance->post_export(file => $filemap , object_type => 'workbook',format => 'html');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ Perl لتصدير الكائنات من المصنف Excel إلى HTML" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>قم باستدعاء طريقة post_export للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
