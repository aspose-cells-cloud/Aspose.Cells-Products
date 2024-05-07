---
title:  تحويل TXT إلى JSON باستخدام Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لتحويل ملف بتنسيق TXT إلى ملف بتنسيق JSON.
kwords: Excel, Convert TXT to JSON, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert TXT to JSON using the Cells Cloud Python library.","description": "How to convert TXT to JSON using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/conversion/txt-to-json/","step": [{ "@type": "HowToStep","name": "How to convert TXT to JSON using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert TXT to JSON using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-json/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert TXT to JSON using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-json/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to convert TXT to JSON using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-json/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل TXT إلى JSON" h2="مكتبة Python لتحويل TXT إلى JSON" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Python. يعد هذا حلاً احترافيًا لتحويل TXT إلى JSON وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Python." urlsection="conversion/txt-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل TXT إلى JSON باستخدام Cells Cloud SDK لـ Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من TXT إلى JSON مهمة معقدة. يتعامل SDK Python الخاص بنا مع جميع تحويلات تنسيق TXT إلى JSON مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات TXT المصدر. توفر مكتبتنا Python حلاً احترافيًا لتحويل ملفات TXT إلى JSON عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Python من الحصول على وظائف قوية ويضمن إخراج JSON عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python مثال على الكود لتحويل TXT إلى JSON باستخدام Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.txt",format="json")
    shutil.move(file1, "destFile.json")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية تحويل TXT إلى JSON باستخدام مكتبة Cells Cloud Python." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Python وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Python.</li>
<li>استخدم طريقة `put_convert_workbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Python 2.7 أو أحدث</li>
<li>Python 3.10 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
