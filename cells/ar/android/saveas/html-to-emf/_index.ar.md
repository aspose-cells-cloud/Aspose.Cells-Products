---
title: احفظ HTML كـ EMF API لأجهزة الأندرويد
description:  استخدام Aspose.Cells Cloud SDK لنظام Android لحفظ ملف بتنسيق HTML كملف بتنسيق EMF.
url: /ar/android/saveas/html-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API لحفظ HTML كـ EMF" h2="مكتبة Android لحفظ HTML كـ EMF" p="استخدم Cells SaveAs REST API لإنشاء مسارات عمل جدول بيانات مخصصة في Android. هذا حل احترافي لحفظ HTML كـ EMF وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Android." urlsection="saveas/html-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف HTML بالشكل EMF في Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من HTML كـ EMF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق HTML إلى EMF بواسطة Android SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات HTML المصدر. تعد مكتبة Android الخاصة بنا حلاً احترافيًا لحفظ HTML كملفات EMF عبر الإنترنت. يوفر Cloud SDK لمطوري Android وظائف قوية وإخراج EMF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Android باستخدام REST API لحفظ HTML بتنسيق EMF" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.html";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.emf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Java API لحفظ HTML كـ EMF" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة cellSaveAsPostDocumentSaveAs للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Android 7 أو أحدث</li>
<li>Java (TM) بيئة وقت التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
