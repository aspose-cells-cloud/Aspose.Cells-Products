---
title:  تحويل XLS إلى XLTM باستخدام PHP
description: استخدام Aspose.Cells Cloud SDK لـ PHP لتحويل ملف بتنسيق XLS إلى ملف بتنسيق XLTM.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل XLS إلى XLTM" h2="مكتبة PHP لتحويل XLS إلى XLTM" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع PHP. يعد هذا حلاً احترافيًا لتحويل XLS إلى XLTM وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام PHP." urlsection="conversion/xls-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل XLS إلى XLTM باستخدام Cells Cloud SDK لـ PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLS إلى XLTM مهمة معقدة. يتعامل SDK PHP الخاص بنا مع جميع تحويلات تنسيق XLS إلى XLTM مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLS المصدر. توفر مكتبتنا PHP حلاً احترافيًا لتحويل ملفات XLS إلى XLTM عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري PHP من الحصول على وظائف قوية ويضمن إخراج XLTM عالي الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP مثال على الكود لتحويل XLS إلى XLTM باستخدام Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xls';    
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ PHP لتحويل ملفات Excel إلى تنسيقات أخرى من XLS إلى XLTM" >}}
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
