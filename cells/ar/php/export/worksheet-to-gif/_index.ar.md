---
title: قم بتصدير ورقة العمل إلى GIF من جدول البيانات باستخدام PHP API
description:  Aspose.Cells Cloud REST API يدعم تصدير {0} إلى {1} تنسيق الملفات باستخدام {2}.
url: /ar/php/export/worksheet-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API لتصدير ورقة العمل إلى ملف GIF" h2="مكتبة PHP لتصدير ورقة العمل إلى ملف GIF" p="استخدم Cells Export REST API لتصدير مهام سير عمل الكائنات الداخلية لجدول البيانات في PHP. هذا حل احترافي لتصدير WORKSHEET إلى ملف بتنسيق GIF من جدول بيانات عبر الإنترنت باستخدام PHP." urlsection="export/worksheet-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن WORKSHEET إلى ملف بتنسيق GIF في PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن WORKSHEET إلى ملف GIF من جدول البيانات مهمة معقدة. يتم تنفيذ انتقالات تصدير ورقة العمل إلى تنسيق GIF بواسطة PHP SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات WORKSHEET المصدر. تعتبر مكتبة PHP الخاصة بنا حلاً احترافيًا لتصدير كائنات WORKSHEET إلى ملفات بتنسيق GIF عبر الإنترنت. يوفر Cloud SDK للمطورين PHP وظائف قوية وإخراج GIF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في PHP باستخدام REST API لتصدير WORKSHEET إلى تنسيق GIF من جدول البيانات" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'worksheet', 'gif' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام PHP API لتصدير ورقة العمل إلى GIF" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة postExport للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>PHP 7.4 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
