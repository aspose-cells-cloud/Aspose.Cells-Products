---
title:  تحويل PNG إلى XLSM باستخدام Perl
description:  استخدام Aspose.Cells Cloud SDK لـ Perl لتحويل ملف بتنسيق PNG إلى ملف بتنسيق XLSM.
kwords: Excel, Convert PNG to XLSM, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert PNG to XLSM using the Cells Cloud Perl library.","description": "How to convert PNG to XLSM using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/conversion/png-to-xlsm/","step": [{ "@type": "HowToStep","name": "How to convert PNG to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/png-to-xlsm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert PNG to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/png-to-xlsm/","text": "Install Perl package and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert PNG to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/png-to-xlsm/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to convert PNG to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/png-to-xlsm/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل PNG إلى XLSM" h2="مكتبة Perl لتحويل PNG إلى XLSM" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Perl. يعد هذا حلاً احترافيًا لتحويل PNG إلى XLSM وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Perl." urlsection="conversion/png-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل PNG إلى XLSM باستخدام Cells Cloud SDK لـ Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من PNG إلى XLSM مهمة معقدة. يتعامل SDK Perl الخاص بنا مع جميع تحويلات تنسيق PNG إلى XLSM مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات PNG المصدر. توفر مكتبتنا Perl حلاً احترافيًا لتحويل PNG إلى ملفات XLSM عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Perl من الحصول على وظائف قوية ويضمن إخراج XLSM عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl مثال على الكود لتحويل PNG إلى XLSM باستخدام Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xlsm";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.png");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.png") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xlsm") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية تحويل PNG إلى XLSM باستخدام مكتبة Cells Cloud Perl." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت حزمة Perl وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Perl.</li>
<li>استخدم طريقة `put_convert_workbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
