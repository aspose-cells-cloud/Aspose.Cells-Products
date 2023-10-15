---
title:  احفظ EMF بصيغة JPG باستخدام Android
description:  استخدام Aspose.Cells Cloud SDK لنظام Android لحفظ ملف بتنسيق EMF كملف بتنسيق JPG.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="احفظ EMF بصيغة JPG" h2="مكتبة Android لحفظ EMF بصيغة JPG" p="استخدم SaveAs API من Cells Cloud لإنشاء مهام سير عمل جدول بيانات مخصصة في Android. يعد هذا حلاً احترافيًا لحفظ EMF بتنسيق JPG وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Android." urlsection="saveas/emf-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف EMF بتنسيق JPG في Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من EMF بتنسيق JPG مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق EMF إلى JPG بواسطة Android SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات EMF. تعد مكتبة Android الخاصة بنا حلاً احترافيًا لحفظ EMF كملفات JPG عبر الإنترنت. يوفر Cloud SDK لمطوري Android وظائف قوية ومخرجات JPG مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على رمز Android لحفظ EMF بصيغة JPG باستخدام REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.emf";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.jpg";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لنظام Android لحفظ Excel ملف بتنسيقات أخرى EMF بصيغة JPG" >}}
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
