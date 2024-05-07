---
title:  احفظ XLSB كـ XPS باستخدام C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لحفظ ملف بتنسيق XLSB كملف بتنسيق XPS.
kwords: Excel, Save XLSB as XPS, REST, C#
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSB as XPS using the Cells Cloud Net library.","description": "How to save XLSB as XPS using the Cells Cloud Net library.","image": {"@type": "ImageObject"},"url": "/net/saveas/xlsb-to-xps/","step": [{ "@type": "HowToStep","name": "How to save XLSB as XPS using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xlsb-to-xps/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSB as XPS using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xlsb-to-xps/","text": "Install C# library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSB as XPS using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xlsb-to-xps/","text": "Open the source file in C#",},{ "@type": "HowToStep","name": "How to save XLSB as XPS using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xlsb-to-xps/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ XLSB كـ XPS" h2="مكتبة C# لحفظ XLSB كـ XPS" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Net. يعد هذا حلاً احترافيًا لحفظ XLSB كـ XPS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="saveas/xlsb-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف XLSB كـ XPS في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من XLSB كـ XPS مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XLSB إلى XPS بواسطة C# SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLSB المصدر. تعد مكتبتنا C# حلاً احترافيًا لحفظ XLSB كملفات XPS عبر الإنترنت. يمنح Cloud SDK هذا مطوري C# وظائف قوية وإخراج XPS مثاليًا.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# مثال على الكود لحفظ XLSB كـ XPS باستخدام REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsb";
    string newfilename = "Book1SaveAs.xps";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية حفظ XLSB كـ XPS باستخدام مكتبة Cells Cloud Net." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة C# وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في C#</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>NET Framework 4.5.2 أو الأحدث</li>
<li>نت ستاندرد 2.0 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
