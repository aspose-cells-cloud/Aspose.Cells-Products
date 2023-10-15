---
title:  تصدير الرسم البياني إلى TIFF من Excel باستخدام Cells Cloud SDK لـ PHP
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تصدير الرسم البياني إلى TIFF من Excel" h2="مكتبة PHP لتصدير الرسم البياني إلى ملف TIFF" p="استخدم تصدير API من Cells Cloud لتصدير سير عمل الكائن الداخلي للملف Excel في PHP. يعد هذا حلاً احترافيًا لتصدير CHART إلى ملف بتنسيق TIFF من جدول البيانات عبر الإنترنت باستخدام PHP." urlsection="export/chart-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن CHART إلى ملف تنسيق TIFF باستخدام Cells Cloud SDK لـ PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن CHART إلى ملف TIFF من ملف Excel مهمة معقدة. يتم تنفيذ انتقالات تنسيق تصدير CHART إلى تنسيق TIFF بواسطة PHP SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات CHART المصدر. تعد مكتبتنا PHP حلاً احترافيًا لتصدير كائنات CHART إلى ملفات بتنسيق TIFF عبر الإنترنت. يمنح Cloud SDK هذا مطوري PHP وظائف قوية وإخراج TIFF مثاليًا.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على الكود في PHP باستخدام REST API لتصدير CHART إلى تنسيق TIFF من جدول البيانات" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\LightCellsApi;
    $cells = new LightCellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $files = array (
        'DataSource' =>  "C:/datasource.xlsx",
        'AssemblyTest' => "C:/assemblytest.xlsx"
    );
    $result = $cells->postExport( $files,'chart', 'tiff' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ PHP لتصدير الكائنات من Excel CHART إلى TIFF" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `postExport` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>PHP 7.4 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
