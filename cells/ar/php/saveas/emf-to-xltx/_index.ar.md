---
title:  احفظ EMF كـ XLTX باستخدام PHP
description:  استخدام Aspose.Cells Cloud SDK لـ PHP لحفظ ملف بتنسيق EMF كملف بتنسيق XLTX.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="احفظ EMF كـ XLTX" h2="مكتبة PHP لحفظ EMF بصيغة XLTX" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جداول بيانات مخصصة في PHP. يعد هذا حلاً احترافيًا لحفظ EMF بتنسيق XLTX وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام PHP." urlsection="saveas/emf-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف EMF بتنسيق XLTX في PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من EMF بتنسيق XLTX مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق EMF إلى XLTX بواسطة PHP SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات EMF. تعد مكتبتنا PHP حلاً احترافيًا لحفظ EMF كملفات XLTX عبر الإنترنت. يوفر Cloud SDK هذا لمطوري PHP وظائف قوية ومخرجات XLTX مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP مثال على الكود لحفظ EMF كـ XLTX باستخدام REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.emf';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "xltx";
    $newfilename = "Book1Saveas.xltx";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ PHP لحفظ ملفات Excel بتنسيقات أخرى EMF بتنسيق XLTX" >}}
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
