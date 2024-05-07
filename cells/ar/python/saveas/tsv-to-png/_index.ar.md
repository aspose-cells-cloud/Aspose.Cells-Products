---
title:  احفظ TSV كـ PNG باستخدام Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لحفظ ملف بتنسيق TSV كملف بتنسيق PNG.
kwords: Excel, Save TSV as PNG, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save TSV as PNG using the Cells Cloud Python library.","description": "How to save TSV as PNG using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/tsv-to-png/","step": [{ "@type": "HowToStep","name": "How to save TSV as PNG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/tsv-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save TSV as PNG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/tsv-to-png/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save TSV as PNG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/tsv-to-png/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save TSV as PNG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/tsv-to-png/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ TSV كـ PNG" h2="مكتبة Python لحفظ TSV برقم PNG" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جداول بيانات مخصصة في Python. يعد هذا حلاً احترافيًا لحفظ TSV كـ PNG وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Python." urlsection="saveas/tsv-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف TSV باسم PNG في Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من TSV بالرقم PNG مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق TSV إلى PNG بواسطة Python SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات TSV المصدر. تعد مكتبتنا Python حلاً احترافيًا لحفظ TSV كملفات PNG عبر الإنترنت. يمنح Cloud SDK هذا مطوري Python وظائف قوية وإخراج PNG مثاليًا.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python مثال على الكود لحفظ TSV كـ PNG باستخدام REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.tsv'    
    saveOptions = None
    newfilename = "Book1Saveas.png"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية حفظ TSV كـ PNG باستخدام مكتبة Cells Cloud Python." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Python وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Python.</li>
<li>استخدم طريقة `post_workbook_save_as` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Python 2.7 أو أحدث</li>
<li>Python 3.10 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
