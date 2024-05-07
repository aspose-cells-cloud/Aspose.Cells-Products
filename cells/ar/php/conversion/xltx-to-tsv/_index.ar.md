---
title:  تحويل XLTX إلى TSV باستخدام PHP
description:  استخدام Aspose.Cells Cloud SDK لـ PHP لتحويل ملف بتنسيق XLTX إلى ملف بتنسيق TSV.
kwords: Excel, Convert XLTX to TSV, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLTX to TSV using the Cells Cloud PHP library.","description": "How to convert XLTX to TSV using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/xltx-to-tsv/","step": [{ "@type": "HowToStep","name": "How to convert XLTX to TSV using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xltx-to-tsv/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLTX to TSV using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xltx-to-tsv/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLTX to TSV using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xltx-to-tsv/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert XLTX to TSV using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xltx-to-tsv/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل XLTX إلى TSV" h2="مكتبة PHP لتحويل XLTX إلى TSV" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع PHP. يعد هذا حلاً احترافيًا لتحويل XLTX إلى TSV وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام PHP." urlsection="conversion/xltx-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل XLTX إلى TSV باستخدام Cells Cloud SDK لـ PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLTX إلى TSV مهمة معقدة. يتعامل SDK PHP الخاص بنا مع جميع تحويلات تنسيق XLTX إلى TSV مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLTX المصدر. توفر مكتبتنا PHP حلاً احترافيًا لتحويل ملفات XLTX إلى ملفات TSV عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري PHP من خلال وظائف قوية ويضمن إخراج TSV عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP مثال على الكود لتحويل XLTX إلى TSV باستخدام Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xltx';    
    $format ='tsv';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.tsv", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية تحويل XLTX إلى TSV باستخدام مكتبة Cells Cloud PHP." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة PHP وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في PHP.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>PHP 7.4 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
