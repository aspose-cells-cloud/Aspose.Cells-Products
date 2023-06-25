---
title:  وفر HTML كـ XLSM API مقابل PHP
description: استخدام Aspose.Cells Cloud SDK لـ PHP لحفظ ملف بتنسيق HTML كملف بتنسيق XLSM.
url: /ar/php/saveas/html-to-xlsm/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API لحفظ HTML كـ XLSM" h2="مكتبة PHP لحفظ HTML كـ XLSM" p="استخدم Cells SaveAs REST API لإنشاء مهام سير عمل جداول بيانات مخصصة في PHP. هذا حل احترافي لحفظ HTML كـ XLSM وتنسيقات مستندات أخرى عبر الإنترنت باستخدام PHP." urlsection="saveas/html-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف HTML كـ XLSM في PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من HTML كـ XLSM مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق HTML إلى XLSM بواسطة PHP SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول البيانات HTML المصدر. تعد مكتبتنا PHP حلاً احترافيًا لحفظ HTML كملفات XLSM عبر الإنترنت. يوفر Cloud SDK للمطورين PHP وظائف قوية وإخراج XLSM مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في PHP باستخدام REST API لحفظ HTML بتنسيق XLSM" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.html';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "xlsm";
    $newfilename = "Book1Saveas.xlsm";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام PHP API لحفظ HTML كـ XLSM" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة cellSaveAsPostDocumentSaveAs للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>PHP 7.4 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
