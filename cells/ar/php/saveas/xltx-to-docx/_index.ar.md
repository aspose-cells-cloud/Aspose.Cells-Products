---
title: احفظ XLTX كـ DOCX باستخدام PHP
description:  استخدام Aspose.Cells Cloud SDK لـ PHP لحفظ ملف بتنسيق XLTX كملف بتنسيق DOCX.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="احفظ XLTX بصيغة DOCX" h2="مكتبة PHP لحفظ XLTX بصيغة DOCX" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جداول بيانات مخصصة في PHP. يعد هذا حلاً احترافيًا لحفظ XLTX بتنسيق DOCX وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام PHP." urlsection="saveas/xltx-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف XLTX بتنسيق DOCX في PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من XLTX بصيغة DOCX مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق XLTX إلى DOCX بواسطة PHP SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLTX المصدر. تعد مكتبتنا PHP حلاً احترافيًا لحفظ XLTX كملفات DOCX عبر الإنترنت. يوفر Cloud SDK لمطوري PHP وظائف قوية ومخرجات DOCX مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP مثال على الكود لحفظ XLTX كـ DOCX باستخدام REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xltx';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "docx";
    $newfilename = "Book1Saveas.docx";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ PHP لحفظ ملفات Excel بتنسيقات أخرى XLTX مثل DOCX" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>PHP 7.4 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
