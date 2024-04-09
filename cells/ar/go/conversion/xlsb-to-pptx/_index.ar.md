---
title:  تحويل XLSB إلى PPTX باستخدام Go
description:  استخدام Aspose.Cells Cloud SDK لـ Go لتحويل ملف بتنسيق XLSB إلى ملف بتنسيق PPTX.
kwords: Excel, Convert XLSB to PPTX, REST, Go
howto: How to convert XLSB to PPTX using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل XLSB إلى PPTX" h2="انتقل إلى المكتبة لتحويل XLSB إلى PPTX" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Go. يعد هذا حلاً احترافيًا لتحويل XLSB إلى PPTX وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Go." urlsection="conversion/xlsb-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="قم بتحويل XLSB إلى PPTX باستخدام Cells Cloud SDK لـ Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLSB إلى PPTX مهمة معقدة. يتعامل Go SDK الخاص بنا مع جميع تحويلات تنسيق XLSB إلى PPTX مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLSB المصدر. توفر مكتبة Go الخاصة بنا حلاً احترافيًا لتحويل ملفات XLSB إلى ملفات PPTX عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Go من الحصول على وظائف قوية ويضمن إخراج PPTX عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="اذهب إلى مثال الكود لتحويل XLSB إلى PPTX باستخدام Cells Cloud SDK" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.xlsb")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "pptx"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.pptx")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية تحويل XLSB إلى PPTX باستخدام مكتبة Cells Cloud Go." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Go وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في الذهاب.</li>
<li>استخدم طريقة `PutConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>انتقل إلى الإصدار go1.13.0 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
