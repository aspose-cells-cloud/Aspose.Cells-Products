---
title: احفظ EMF كـ JSON باستخدام Java
description:  استخدام Aspose.Cells Cloud SDK for Java لحفظ ملف بتنسيق EMF كملف بتنسيق JSON.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="احفظ EMF بتنسيق JSON" h2="مكتبة Java لحفظ EMF بصيغة JSON" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جداول بيانات مخصصة في Java. يعد هذا حلاً احترافيًا لحفظ EMF بتنسيق JSON وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Java." urlsection="saveas/emf-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف EMF بتنسيق JSON في Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من EMF بتنسيق JSON مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق EMF إلى JSON بواسطة Java SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات EMF. تعد مكتبتنا Java حلاً احترافيًا لحفظ EMF كملفات JSON عبر الإنترنت. يوفر Cloud SDK هذا لمطوري Java وظائف قوية ومخرجات JSON مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java مثال على الكود لحفظ EMF كـ JSON باستخدام REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.emf";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.json";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK for Java لحفظ Excel ملف بتنسيقات أخرى EMF كـ JSON" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `postWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Maven 2.2.0 أو أحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
