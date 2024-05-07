---
title:  احفظ XLTX بصيغة GIF باستخدام PHP
description: استخدام Aspose.Cells Cloud SDK لـ PHP لحفظ ملف بتنسيق XLTX كملف بتنسيق GIF.
kwords: Excel, Save XLTX as GIF, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLTX as GIF using the Cells Cloud PHP library.","description": "How to save XLTX as GIF using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/saveas/xltx-to-gif/","step": [{ "@type": "HowToStep","name": "How to save XLTX as GIF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xltx-to-gif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLTX as GIF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xltx-to-gif/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLTX as GIF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xltx-to-gif/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to save XLTX as GIF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xltx-to-gif/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ XLTX بصيغة GIF" h2="مكتبة PHP لحفظ XLTX بصيغة GIF" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جداول بيانات مخصصة في PHP. يعد هذا حلاً احترافيًا لحفظ XLTX بتنسيق GIF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام PHP." urlsection="saveas/xltx-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف XLTX بتنسيق GIF في PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من XLTX بتنسيق GIF مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق XLTX إلى GIF بواسطة PHP SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLTX المصدر. تعد مكتبتنا PHP حلاً احترافيًا لحفظ XLTX كملفات GIF عبر الإنترنت. يوفر Cloud SDK هذا لمطوري PHP وظائف قوية ومخرجات GIF مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP مثال على الكود لحفظ XLTX بصيغة GIF باستخدام REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xltx';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "gif";
    $newfilename = "Book1Saveas.gif";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية حفظ XLTX بصيغة GIF باستخدام مكتبة Cells Cloud PHP." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة PHP وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في PHP.</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>PHP 7.4 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
