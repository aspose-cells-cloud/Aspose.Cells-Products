---
title:  تحويل HTML إلى XLTM باستخدام PHP
description:  استخدام Aspose.Cells Cloud SDK لـ PHP لتحويل ملف بتنسيق HTML إلى ملف بتنسيق XLTM.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل HTML إلى XLTM" h2="مكتبة PHP لتحويل HTML إلى XLTM" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع PHP. يعد هذا حلاً احترافيًا لتحويل HTML إلى XLTM وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام PHP." urlsection="conversion/html-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل HTML إلى XLTM باستخدام Cells Cloud SDK لـ PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من HTML إلى XLTM مهمة معقدة. يتعامل SDK PHP الخاص بنا مع جميع تحويلات تنسيق HTML إلى XLTM مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات HTML المصدر. توفر مكتبتنا PHP حلاً احترافيًا لتحويل HTML إلى ملفات XLTM عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري PHP من الحصول على وظائف قوية ويضمن إخراج XLTM عالي الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP مثال على الكود لتحويل HTML إلى XLTM باستخدام Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.html';    
    $format ='xltm';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xltm", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ PHP لتحويل ملفات Excel إلى تنسيقات أخرى HTML إلى XLTM" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>PHP 7.4 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
