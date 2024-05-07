---
title:  احفظ المواد المستنفدة للأوزون بصيغة GIF باستخدام Perl
description:  استخدام Aspose.Cells Cloud SDK لـ Perl لحفظ ملف بتنسيق ODS كملف بتنسيق GIF.
kwords: Excel, Save ODS as GIF, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save ODS as GIF using the Cells Cloud Perl library.","description": "How to save ODS as GIF using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/saveas/ods-to-gif/","step": [{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/ods-to-gif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/ods-to-gif/","text": "Install Perl library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/ods-to-gif/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to save ODS as GIF using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/ods-to-gif/","text": "Call post_workbook_save_as method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="حفظ المواد المستنفدة للأوزون بصيغة GIF" h2="Perl مكتبة لحفظ المواد المستنفدة للأوزون بصيغة GIF" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جداول بيانات مخصصة في Perl. يعد هذا حلاً احترافيًا لحفظ المواد المستنفدة للأوزون بتنسيق GIF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Perl." urlsection="saveas/ods-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف ODS بصيغة GIF في Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من ODS بتنسيق GIF مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق ODS إلى GIF بواسطة Perl SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات ODS المصدر. تعد مكتبتنا Perl حلاً احترافيًا لحفظ المواد المستنفدة للأوزون كملفات GIF عبر الإنترنت. يوفر Cloud SDK هذا لمطوري Perl وظائف قوية ومخرجات GIF مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl مثال على الكود لحفظ المواد المستنفدة للأوزون بصيغة GIF باستخدام REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.ods';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.gif';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية حفظ المواد المستنفدة للأوزون بصيغة GIF باستخدام مكتبة Cells Cloud Perl." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Perl وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Perl.</li>
<li>اتصل بالبريد_دفتر العمل_طريقة save_as للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
