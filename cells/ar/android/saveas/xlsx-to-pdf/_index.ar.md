﻿---
title:  احفظ XLSX كـ PDF باستخدام Android
description:  استخدام Aspose.Cells Cloud SDK لنظام Android لحفظ ملف بتنسيق XLSX كملف بتنسيق PDF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="احفظ XLSX كـ PDF" h2="مكتبة Android لحفظ XLSX كـ PDF" p="استخدم SaveAs API من Cells Cloud لإنشاء مهام سير عمل جدول بيانات مخصصة في Android. يعد هذا حلاً احترافيًا لحفظ XLSX كـ PDF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Android." urlsection="saveas/xlsx-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف XLSX باسم PDF في Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من XLSX كـ PDF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XLSX إلى PDF بواسطة Android SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLSX المصدر. تعد مكتبة Android الخاصة بنا حلاً احترافيًا لحفظ XLSX كملفات PDF عبر الإنترنت. يوفر Cloud SDK لمطوري Android وظائف قوية وإخراجًا مثاليًا PDF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على رمز Android لحفظ XLSX كـ PDF باستخدام REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xlsx";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.pdf";
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
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لنظام Android لحفظ ملفات Excel بتنسيقات أخرى XLSX مثل PDF" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `postWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>أندرويد 7 أو الأحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
