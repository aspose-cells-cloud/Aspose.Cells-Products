---
title:  تصدير الصورة إلى EMF من Excel باستخدام Cells Cloud SDK لـ Perl
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تصدير الصورة إلى EMF من Excel" h2="مكتبة Perl لتصدير الصور إلى ملف EMF" p="استخدم تصدير API من Cells Cloud لتصدير سير عمل الكائن الداخلي للملف Excel في Perl. هذا حل احترافي لتصدير PICTURE إلى ملف بتنسيق EMF من جدول البيانات عبر الإنترنت باستخدام Perl." urlsection="export/picture-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن PICTURE إلى ملف بتنسيق EMF باستخدام Cells Cloud SDK لـ Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن PICTURE إلى ملف EMF من ملف Excel مهمة معقدة. يتم تنفيذ انتقالات تنسيق تصدير PICTURE إلى تنسيق EMF بواسطة Perl SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات PICTURE المصدر. تعد مكتبتنا Perl حلاً احترافيًا لتصدير كائنات PICTURE إلى ملفات بتنسيق EMF عبر الإنترنت. يمنح Cloud SDK هذا مطوري Perl وظائف قوية وإخراج EMF مثاليًا.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على الكود في Perl باستخدام REST API لتصدير الصورة إلى تنسيق EMF من جدول البيانات" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'picture',format => 'emf');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ Perl لتصدير الكائنات من Excel PICTURE إلى EMF" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>قم باستدعاء طريقة post_export للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
