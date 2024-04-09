---
title:  احفظ الأطعمة كمواد مستنفدة للأوزون باستخدام C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لحفظ ملف تنسيق FODS كملف تنسيق ODS.
kwords: Excel, Save FODS as ODS, REST, C#
howto: How to save FODS as ODS using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="حفظ الأطعمة كمواد مستنفدة للأوزون" h2="C# مكتبة حفظ الأطعمة كمواد مستنفدة للأوزون" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Net. يعد هذا حلاً احترافيًا لحفظ FODS كملف ODS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="saveas/fods-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف FODS باسم ODS في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من FODS كمواد مستنفدة للأوزون مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق FODS إلى ODS بواسطة C# SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات FODS. تعد مكتبتنا C# حلاً احترافيًا لحفظ FODS كملفات ODS عبر الإنترنت. يوفر Cloud SDK هذا لمطوري C# وظائف قوية ومخرجات مثالية للمواد المستنفدة للأوزون.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# مثال كودي لحفظ الأطعمة كمواد مستنفدة للأوزون باستخدام REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.fods";
    string newfilename = "Book1SaveAs.ods";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية حفظ FODS كملف ODS باستخدام مكتبة Cloud Net Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة C# وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في C#</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>NET Framework 4.5.2 أو أحدث</li>
<li>نت ستاندرد 2.0 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
