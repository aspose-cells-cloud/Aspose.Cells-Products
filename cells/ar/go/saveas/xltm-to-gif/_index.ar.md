﻿---
title:  احفظ XLTM بصيغة GIF باستخدام Go
description:  استخدام Aspose.Cells Cloud SDK لـ Go لحفظ ملف بتنسيق XLTM كملف بتنسيق GIF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="احفظ XLTM بصيغة GIF" h2="انتقل إلى المكتبة لحفظ XLTM بصيغة GIF" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Go. يعد هذا حلاً احترافيًا لحفظ XLTM بتنسيق GIF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Go." urlsection="saveas/xltm-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف XLTM بتنسيق GIF في Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من XLTM بتنسيق GIF مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق XLTM إلى GIF بواسطة Go SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLTM المصدر. تعد مكتبة Go الخاصة بنا حلاً احترافيًا لحفظ XLTM كملفات GIF عبر الإنترنت. يمنح Cloud SDK لمطوري Go وظائف قوية ومخرجات GIF مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="انتقل إلى مثال الرمز لحفظ XLTM بتنسيق GIF باستخدام REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.xltm"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.gif"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ Go لحفظ ملفات Excel بتنسيقات أخرى XLTM مثل GIF" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>انتقل إلى الإصدار go1.13.0 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
