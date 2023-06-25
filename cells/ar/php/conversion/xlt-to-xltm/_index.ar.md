---
title:  XLT إلى XLTM تحويل API لـ PHP
description:  استخدام Aspose.Cells Cloud SDK لـ PHP لتحويل ملف تنسيق XLT إلى ملف بتنسيق XLTM.
url: /ar/php/conversion/xlt-to-xltm/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API لتحويل XLT إلى XLTM" h2="PHP مكتبة لتحويل XLT إلى XLTM" p="استخدم Cells Conversion REST API لإنشاء جداول سير عمل مخصصة لجداول البيانات في PHP. هذا حل احترافي لتحويل XLT إلى XLTM وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام PHP." urlsection="conversion/xlt-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف XLT إلى XLTM في PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من XLT إلى XLTM مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XLT إلى XLTM بواسطة PHP SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات XLT المصدر. تعد مكتبتنا PHP حلاً احترافيًا لتحويل ملفات XLT إلى XLTM عبر الإنترنت. يوفر Cloud SDK للمطورين PHP وظائف قوية وإخراج XLTM مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في PHP باستخدام REST API لتحويل XLT إلى تنسيق XLTM" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlt';    
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام PHP API لتحويل XLT إلى XLTM" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة cellWorkbookPutConvertWorkBook للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>PHP 7.4 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
