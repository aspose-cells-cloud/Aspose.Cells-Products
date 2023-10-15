---
title:  احفظ المواد المستنفدة للأوزون مثل FODS باستخدام Perl
description:  استخدام Aspose.Cells Cloud SDK لـ Perl لحفظ ملف تنسيق ODS كملف تنسيق FODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="حفظ المواد المستنفدة للأوزون كأغذية FODS" h2="Perl مكتبة حفظ المواد المستنفدة للأوزون على هيئة FODS" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جداول بيانات مخصصة في Perl. يعد هذا حلاً احترافيًا لحفظ المواد المستنفدة للأوزون مثل FODS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Perl." urlsection="saveas/ods-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف ODS باسم FODS في Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من المواد المستنفدة للأوزون باسم FODS مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق ODS إلى FODS بواسطة Perl SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات ODS. تعد مكتبتنا Perl حلاً احترافيًا لحفظ المواد المستنفدة للأوزون كملفات FODS عبر الإنترنت. يوفر Cloud SDK هذا لمطوري Perl وظائف قوية ومخرجات FODS مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl مثال كودي لحفظ المواد المستنفدة للأوزون على هيئة FODS باستخدام REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.ods';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.fods';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ Perl لحفظ ملفات Excel بتنسيقات أخرى ODS مثل FODS" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>اتصل بالبريد_دفتر العمل_طريقة save_as للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
