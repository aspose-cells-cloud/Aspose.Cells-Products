---
title:  احفظ المواد المستنفدة للأوزون مثل FODS باستخدام C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لحفظ ملف تنسيق ODS كملف تنسيق FODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="حفظ المواد المستنفدة للأوزون كأغذية FODS" h2="C# مكتبة حفظ المواد المستنفدة للأوزون على هيئة FODS" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Net. يعد هذا حلاً احترافيًا لحفظ المواد المستنفدة للأوزون مثل FODS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="saveas/ods-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف ODS باسم FODS في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من المواد المستنفدة للأوزون باسم FODS مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق ODS إلى FODS بواسطة C# SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات ODS. تعد مكتبتنا C# حلاً احترافيًا لحفظ المواد المستنفدة للأوزون كملفات FODS عبر الإنترنت. يوفر Cloud SDK هذا لمطوري C# وظائف قوية ومخرجات FODS مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# مثال كودي لحفظ المواد المستنفدة للأوزون على هيئة FODS باستخدام REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.ods";
    string newfilename = "Book1SaveAs.fods";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK for Net لحفظ ملفات Excel بتنسيقات أخرى ODS مثل FODS" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>NET Framework 4.5.2 أو أحدث</li>
<li>نت ستاندرد 2.0 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
