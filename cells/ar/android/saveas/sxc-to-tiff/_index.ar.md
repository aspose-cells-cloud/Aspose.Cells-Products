﻿---
title:  احفظ SXC كـ TIFF باستخدام Android
description:  استخدام Aspose.Cells Cloud SDK لنظام Android لحفظ ملف بتنسيق SXC كملف بتنسيق TIFF.
kwords: Excel, Save SXC as TIFF, REST, Android
howto: How to save SXC as TIFF using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ SXC كـ TIFF" h2="مكتبة Android لحفظ SXC كـ TIFF" p="استخدم SaveAs API من Cells Cloud لإنشاء مهام سير عمل جدول بيانات مخصصة في Android. يعد هذا حلاً احترافيًا لحفظ SXC كـ TIFF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Android." urlsection="saveas/sxc-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف SXC باسم TIFF في Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من SXC كـ TIFF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق SXC إلى TIFF بواسطة Android SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات SXC المصدر. تعد مكتبة Android الخاصة بنا حلاً احترافيًا لحفظ SXC كملفات TIFF عبر الإنترنت. يوفر Cloud SDK لمطوري Android وظائف قوية وإخراجًا مثاليًا TIFF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على رمز Android لحفظ SXC كـ TIFF باستخدام REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.sxc";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.tiff";
    String folder ="CellsTests";
    try
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لنظام Android لحفظ ملفات Excel بتنسيقات أخرى" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `postWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>أندرويد 7 أو الأحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
