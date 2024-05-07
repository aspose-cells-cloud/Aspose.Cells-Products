---
title:  تحويل PNG إلى XLSX باستخدام PHP
description:  استخدام Aspose.Cells Cloud SDK لـ PHP لتحويل ملف بتنسيق PNG إلى ملف بتنسيق XLSX.
kwords: Excel, Convert PNG to XLSX, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert PNG to XLSX using the Cells Cloud PHP library.","description": "How to convert PNG to XLSX using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/png-to-xlsx/","step": [{ "@type": "HowToStep","name": "How to convert PNG to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/png-to-xlsx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert PNG to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/png-to-xlsx/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert PNG to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/png-to-xlsx/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert PNG to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/png-to-xlsx/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل PNG إلى XLSX" h2="مكتبة PHP لتحويل PNG إلى XLSX" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع PHP. يعد هذا حلاً احترافيًا لتحويل PNG إلى XLSX وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام PHP." urlsection="conversion/png-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل PNG إلى XLSX باستخدام Cells Cloud SDK لـ PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من PNG إلى XLSX مهمة معقدة. يتعامل SDK PHP الخاص بنا مع جميع تحويلات تنسيق PNG إلى XLSX مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات PNG المصدر. توفر مكتبتنا PHP حلاً احترافيًا لتحويل PNG إلى ملفات XLSX عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري PHP من الحصول على وظائف قوية ويضمن إخراج XLSX عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP مثال على الكود لتحويل PNG إلى XLSX باستخدام Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.png';    
    $format ='xlsx';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xlsx", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية تحويل PNG إلى XLSX باستخدام مكتبة Cells Cloud PHP." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة PHP وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في PHP.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>PHP 7.4 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
