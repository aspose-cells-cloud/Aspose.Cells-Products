---
title:  احفظ ODS بتنسيق XLTM باستخدام Go
description:  استخدام Aspose.Cells Cloud SDK لـ Go لحفظ ملف بتنسيق ODS كملف بتنسيق XLTM.
kwords: Excel, Save ODS as XLTM, REST, Go
howto: How to save ODS as XLTM using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ المواد المستنفدة للأوزون باسم XLTM" h2="انتقل إلى المكتبة لحفظ المواد المستنفدة للأوزون بتنسيق XLTM" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Go. يعد هذا حلاً احترافيًا لحفظ المواد المستنفدة للأوزون بتنسيق XLTM وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Go." urlsection="saveas/ods-to-xltm/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف ODS بتنسيق XLTM في Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من ODS بتنسيق XLTM مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق ODS إلى XLTM بواسطة Go SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات ODS المصدر. تعد مكتبة Go الخاصة بنا حلاً احترافيًا لحفظ المواد المستنفدة للأوزون كملفات XLTM عبر الإنترنت. يمنح Cloud SDK لمطوري Go وظائف قوية ومخرجات XLTM مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="اذهب إلى مثال الرمز لحفظ المواد المستنفدة للأوزون كـ XLTM باستخدام REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.ods"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xltm"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية حفظ ODS بتنسيق XLTM باستخدام مكتبة Cloud Go Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Go وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في الذهاب.</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>انتقل إلى الإصدار go1.13.0 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
