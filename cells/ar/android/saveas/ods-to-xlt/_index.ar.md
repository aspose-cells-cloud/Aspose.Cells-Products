---
title:  احفظ ODS كـ XLT API لنظام Android
description: استخدام Aspose.Cells Cloud SDK لنظام Android لحفظ ملف بتنسيق ODS كملف بتنسيق XLT.
url: /ar/android/saveas/ods-to-xlt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API لحفظ ODS كـ XLT" h2="مكتبة Android لحفظ ODS كـ XLT" p="استخدم Cells SaveAs REST API لإنشاء مسارات عمل جداول بيانات مخصصة في Android. هذا حل احترافي لحفظ ODS بتنسيق XLT وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Android." urlsection="saveas/ods-to-xlt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف ODS باسم XLT في Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من ODS كـ XLT مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق ODS إلى XLT بواسطة Android SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات ODS. مكتبة Android الخاصة بنا هي حل احترافي لحفظ ODS كملفات XLT عبر الإنترنت. يوفر Cloud SDK لمطوري Android وظائف قوية وإخراج XLT مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Android باستخدام REST API لحفظ ODS بتنسيق XLT" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.ods";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xlt";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Java API لحفظ ODS كـ XLT" >}}
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
