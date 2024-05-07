---
title:  تحويل NUMBERS إلى WMF باستخدام Go
description:  استخدام Aspose.Cells Cloud SDK لـ Go لتحويل ملف بتنسيق NUMBERS إلى ملف بتنسيق WMF.
kwords: Excel, Convert NUMBERS to WMF, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert NUMBERS to WMF using the Cells Cloud Go library.","description": "How to convert NUMBERS to WMF using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/conversion/numbers-to-wmf/","step": [{ "@type": "HowToStep","name": "How to convert NUMBERS to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/numbers-to-wmf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert NUMBERS to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/numbers-to-wmf/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/numbers-to-wmf/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/numbers-to-wmf/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل NUMBERS إلى WMF" h2="انتقل إلى المكتبة لتحويل NUMBERS إلى WMF" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Go. يعد هذا حلاً احترافيًا لتحويل NUMBERS إلى WMF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Go." urlsection="conversion/numbers-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="قم بتحويل NUMBERS إلى WMF باستخدام Cells Cloud SDK for Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من NUMBERS إلى WMF مهمة معقدة. يتعامل Go SDK الخاص بنا مع جميع تحويلات تنسيق NUMBERS إلى WMF مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات NUMBERS المصدر. توفر مكتبة Go الخاصة بنا حلاً احترافيًا لتحويل NUMBERS إلى ملفات WMF عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Go من الحصول على وظائف قوية ويضمن إخراج WMF عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="اذهب إلى مثال الكود لتحويل NUMBERS إلى WMF باستخدام Cells Cloud SDK" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.numbers")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "wmf"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.wmf")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية تحويل NUMBERS إلى WMF باستخدام مكتبة Cells Cloud Go." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Go وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في الذهاب.</li>
<li>استخدم طريقة `PutConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>انتقل إلى الإصدار go1.13.0 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
