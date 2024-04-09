---
title:  احفظ ملف CSV بتنسيق TSV باستخدام Android
description:  استخدام Aspose.Cells Cloud SDK لنظام Android لحفظ ملف بتنسيق CSV كملف بتنسيق TSV.
kwords: Excel, Save CSV as TSV, REST, Android
howto: How to save CSV as TSV using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ ملف CSV بتنسيق TSV" h2="مكتبة Android لحفظ ملف CSV بتنسيق TSV" p="استخدم SaveAs API من Cells Cloud لإنشاء مهام سير عمل جدول بيانات مخصصة في Android. يعد هذا حلاً احترافيًا لحفظ ملف CSV بتنسيق TSV وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Android." urlsection="saveas/csv-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف CSV بتنسيق TSV في Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من CSV بتنسيق TSV مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق CSV إلى TSV بواسطة Android SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات CSV المصدر. تعد مكتبة Android الخاصة بنا حلاً احترافيًا لحفظ ملف CSV كملفات TSV عبر الإنترنت. يوفر Cloud SDK لمطوري Android وظائف قوية ومخرجات TSV مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على رمز Android لحفظ ملف CSV كـ TSV باستخدام REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.csv";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.tsv";
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
