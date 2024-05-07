---
title:  احفظ الأرقام كـ PDF باستخدام Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لحفظ ملف بتنسيق NUMBERS كملف بتنسيق PDF.
kwords: Excel, Save NUMBERS as PDF, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save NUMBERS as PDF using the Cells Cloud Python library.","description": "How to save NUMBERS as PDF using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/numbers-to-pdf/","step": [{ "@type": "HowToStep","name": "How to save NUMBERS as PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/numbers-to-pdf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save NUMBERS as PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/numbers-to-pdf/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save NUMBERS as PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/numbers-to-pdf/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save NUMBERS as PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/numbers-to-pdf/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ الأرقام كـ PDF" h2="مكتبة Python لحفظ الارقام برقم PDF" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جداول بيانات مخصصة في Python. يعد هذا حلاً احترافيًا لحفظ NUMBERS كـ PDF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Python." urlsection="saveas/numbers-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف NUMBERS باسم PDF في Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من NUMBERS بالرقم PDF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق NUMBERS إلى PDF بواسطة Python SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات NUMBERS المصدر. تعد مكتبتنا Python حلاً احترافيًا لحفظ الأرقام كملفات PDF عبر الإنترنت. يمنح Cloud SDK هذا مطوري Python وظائف قوية وإخراج PDF مثاليًا.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python مثال على كود حفظ الأرقام كـ PDF باستخدام REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.numbers'    
    saveOptions = None
    newfilename = "Book1Saveas.pdf"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية حفظ الأرقام كـ PDF باستخدام مكتبة Cells السحابية Python." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Python وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Python.</li>
<li>استخدم طريقة `post_workbook_save_as` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Python 2.7 أو أحدث</li>
<li>Python 3.10 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
