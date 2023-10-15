---
title:  تصدير ورقة عمل إلى PPTX من Excel باستخدام Cells Cloud SDK لـ PHP
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تصدير ورقة العمل إلى PPTX من Excel" h2="مكتبة PHP لتصدير ورقة العمل إلى ملف PPTX" p="استخدم تصدير API من Cells Cloud لتصدير سير عمل الكائن الداخلي للملف Excel في PHP. يعد هذا حلاً احترافيًا لتصدير ورقة العمل إلى ملف بتنسيق PPTX من جدول البيانات عبر الإنترنت باستخدام PHP." urlsection="export/worksheet-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن ورقة العمل إلى ملف بتنسيق PPTX باستخدام Cells Cloud SDK لـ PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن ورقة العمل إلى ملف PPTX من الملف Excel مهمة معقدة. يتم تنفيذ انتقالات تصدير ورقة العمل إلى تنسيق PPTX بواسطة PHP SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات المصدر. تعد مكتبتنا PHP حلاً احترافيًا لتصدير كائنات ورقة العمل إلى ملفات بتنسيق PPTX عبر الإنترنت. يوفر Cloud SDK هذا لمطوري PHP وظائف قوية ومخرجات PPTX مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على الكود في PHP باستخدام REST API لتصدير ورقة عمل إلى تنسيق PPTX من جدول البيانات" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'worksheet', 'pptx' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ PHP لتصدير الكائنات من ورقة عمل Excel إلى PPTX" >}}
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
