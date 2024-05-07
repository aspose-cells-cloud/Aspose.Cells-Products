---
title:  تصدير المصنف إلى MARKDOWN من Excel باستخدام Cells Cloud SDK لـ Python
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
kwords: Excel, workbook, markdown, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to MARKDOWN","description": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to MARKDOWN","image": {"@type": "ImageObject"},"url": "/python/export/workbook-to-markdown/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to MARKDOWN step 1", "image": {"@type": "ImageObject",},"url": "/python/export/workbook-to-markdown/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to MARKDOWN step 1", "image": {"@type": "ImageObject",},"url": "/python/export/workbook-to-markdown/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to MARKDOWN step 1", "image": {"@type": "ImageObject",},"url": "/python/export/workbook-to-markdown/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تصدير المصنف إلى MARKDOWN من Excel" h2="مكتبة Python لتصدير المصنف إلى ملف MARKDOWN" p="استخدم تصدير API من Cells Cloud لتصدير سير عمل الكائن الداخلي للملف Excel في Python. هذا حل احترافي لتصدير WORKBOOK إلى ملف بتنسيق MARKDOWN من جدول البيانات عبر الإنترنت باستخدام Python." urlsection="export/workbook-to-markdown/" >}}

{{< blocks/products/cells/cells-cloud-section title="تصدير كائن كتاب العمل إلى ملف تنسيق MARKDOWN باستخدام Cells Cloud SDK لـ Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن WORKBOOK إلى ملف MARKDOWN من ملف Excel مهمة معقدة. يتم تنفيذ انتقالات تنسيق WORKBOOK إلى MARKDOWN بواسطة Python SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات WORKBOOK المصدر. تعد مكتبتنا Python حلاً احترافيًا لتصدير كائنات WORKBOOK إلى ملفات بتنسيق MARKDOWN عبر الإنترنت. يوفر Cloud SDK هذا لمطوري Python وظائف قوية ومخرجات MARKDOWN مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال للتعليمات البرمجية في Python باستخدام REST API لتصدير المصنف إلى تنسيق MARKDOWN من جدول البيانات" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import base64
    from asposecellscloud.apis.light_cells_api import LightCellsApi
    cells_api = LightCellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    files ={ 
        "myDocument.xlsx" :  "c:/myDocument.xlsx",
        "Book1.xlsx" :  "c:/Book1.xlsx" 
        }
    result = cells_api.post_export(files ,"workbook","markdown")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ Python لتصدير الكائنات من كتاب العمل Excel إلى MARKDOWN" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>قم باستدعاء طريقة post_export للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Python 2.7 أو أحدث</li>
<li>Python 3.10 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
