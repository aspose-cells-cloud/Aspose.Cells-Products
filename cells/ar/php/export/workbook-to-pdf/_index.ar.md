﻿---
title:  تصدير كتاب العمل إلى PDF من جدول البيانات باستخدام PHP API
description:  Aspose.Cells Cloud REST API يدعم تصدير ملف Excel وكائنات داخلية لأنواع ملفات النسق. SDK يدعم أنواع لغات التطوير. وهي تشمل Android و C# و Go و Java و NodeJS و Perl و PHP و Python و Ruby و swift.
url: /ar/php/export/workbook-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API لتصدير دفتر العمل إلى ملف PDF" h2="مكتبة PHP لتصدير كتاب العمل إلى ملف PDF" p="استخدم Cells Export REST API لتصدير مهام سير عمل العناصر الداخلية لجدول البيانات في PHP. هذا حل احترافي لتصدير WORKBOOK إلى ملف بتنسيق PDF من جدول بيانات عبر الإنترنت باستخدام PHP." urlsection="export/workbook-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن WORKBOOK إلى ملف بتنسيق PDF بتنسيق PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن WORKBOOK إلى ملف PDF من جدول البيانات مهمة معقدة. تصدير كتاب العمل إلى PDF يتم تنفيذ انتقالات تنسيق بواسطة PHP SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات WORKBOOK المصدر. تعتبر مكتبة PHP الخاصة بنا حلاً احترافيًا لتصدير كائنات WORKBOOK إلى ملفات بتنسيق PDF عبر الإنترنت. يوفر Cloud SDK للمطورين PHP وظائف قوية وإخراج PDF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال التعليمات البرمجية في PHP باستخدام REST API لتصدير كتاب العمل إلى تنسيق PDF من جدول البيانات" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'workbook', 'pdf' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام PHP API لتصدير كتاب العمل إلى PDF" >}}
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