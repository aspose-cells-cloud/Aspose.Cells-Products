---
title:  احفظ ODS بتنسيق SQL باستخدام Go
description:  استخدام Aspose.Cells Cloud SDK لـ Go لحفظ ملف تنسيق ODS كملف تنسيق SQL.
kwords: Excel, Save ODS as SQL, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save ODS as SQL using the Cells Cloud Go library.","description": "How to save ODS as SQL using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/ods-to-sql/","step": [{ "@type": "HowToStep","name": "How to save ODS as SQL using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/ods-to-sql/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save ODS as SQL using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/ods-to-sql/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save ODS as SQL using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/ods-to-sql/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save ODS as SQL using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/ods-to-sql/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="حفظ المواد المستنفدة للأوزون بتنسيق SQL" h2="انتقل إلى المكتبة لحفظ المواد المستنفدة للأوزون بتنسيق SQL" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Go. يعد هذا حلاً احترافيًا لحفظ المواد المستنفدة للأوزون بتنسيق SQL وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Go." urlsection="saveas/ods-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف ODS بتنسيق SQL في Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من ODS بتنسيق SQL مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق ODS إلى SQL بواسطة Go SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات ODS المصدر. تعد مكتبة Go الخاصة بنا حلاً احترافيًا لحفظ المواد المستنفدة للأوزون كملفات SQL عبر الإنترنت. يمنح Cloud SDK لمطوري Go وظائف قوية ومخرجات SQL مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="انتقل إلى مثال التعليمات البرمجية لحفظ المواد المستنفدة للأوزون كـ SQL باستخدام REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.ods"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.sql"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية حفظ ODS كـ SQL باستخدام مكتبة Cells Cloud Go." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Go وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في الذهاب.</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>انتقل إلى الإصدار go1.13.0 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
