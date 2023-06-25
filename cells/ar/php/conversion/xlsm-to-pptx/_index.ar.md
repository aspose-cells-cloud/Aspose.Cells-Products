---
title:  XLSM إلى PPTX تحويل API إلى PHP
description:  استخدام Aspose.Cells Cloud SDK لـ PHP لتحويل ملف تنسيق XLSM إلى ملف بتنسيق PPTX.
url: /ar/php/conversion/xlsm-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API لتحويل XLSM إلى PPTX" h2="PHP مكتبة لتحويل XLSM إلى PPTX" p="استخدم Cells Conversion REST API لإنشاء تدفقات عمل جداول بيانات مخصصة في PHP. هذا حل احترافي لتحويل XLSM إلى PPTX وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام PHP." urlsection="conversion/xlsm-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف XLSM إلى PPTX في PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من XLSM إلى PPTX مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XLSM إلى PPTX بواسطة PHP SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات XLSM المصدر. مكتبتنا PHP هي حل احترافي لتحويل ملفات XLSM إلى PPTX عبر الإنترنت. يوفر Cloud SDK للمطورين PHP وظائف قوية وإخراج PPTX مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في PHP باستخدام REST API لتحويل XLSM إلى تنسيق PPTX" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlsm';    
    $format ='pptx';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.pptx", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام PHP API لتحويل XLSM إلى PPTX" >}}
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
