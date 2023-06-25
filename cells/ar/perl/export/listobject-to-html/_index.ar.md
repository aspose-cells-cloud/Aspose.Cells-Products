---
title:  قم بتصدير LISTOBJECT إلى HTML من جدول البيانات باستخدام Perl API
description:  Aspose.Cells Cloud REST API يدعم تصدير {0} إلى {1} تنسيق الملفات باستخدام {2}.
url: /ar/perl/export/listobject-to-html/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API لتصدير LISTOBJECT إلى ملف HTML" h2="مكتبة Perl لتصدير LISTOBJECT إلى ملف HTML" p="استخدم Cells Export REST API لتصدير مهام سير عمل العناصر الداخلية لجدول البيانات في Perl. هذا حل احترافي لتصدير LISTOBJECT إلى ملف بتنسيق HTML من جدول بيانات عبر الإنترنت باستخدام Perl." urlsection="export/listobject-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتصدير كائن LISTOBJECT إلى ملف بتنسيق HTML بتنسيق Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير عنصر LISTOBJECT إلى ملف HTML من جدول البيانات مهمة معقدة. تصدير LISTOBJECT إلى HTML يتم تنفيذ انتقالات تنسيق بواسطة Perl SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات LISTOBJECT المصدر. تعتبر مكتبة Perl الخاصة بنا حلاً احترافيًا لتصدير كائنات LISTOBJECT إلى ملفات بتنسيق HTML عبر الإنترنت. يوفر Cloud SDK للمطورين Perl وظائف قوية وإخراج HTML مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Perl باستخدام REST API لتصدير LISTOBJECT إلى تنسيق HTML من جدول البيانات" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'listobject',format => 'html');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Perl API لتصدير LISTOBJECT إلى HTML" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>اتصل بطريقة post_export للحصول على التدفق الناتج </li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
