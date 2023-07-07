---
title:  احفظ XML كـ MD API لـ Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لحفظ ملف بتنسيق XML كملف بتنسيق MD.
url: /ar/python/saveas/xml-to-md/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API لحفظ XML كملف MD" h2="مكتبة Python لحفظ XML كـ MD" p="استخدم Cells SaveAs REST API لإنشاء مسارات عمل جداول بيانات مخصصة في Python. هذا حل احترافي لحفظ XML كـ MD وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Python." urlsection="saveas/xml-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف XML كملف MD في Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من XML كـ MD مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XML إلى MD بواسطة Python SDK مع الحفاظ على المحتوى البنيوي والمنطقي الرئيسي لجدول بيانات XML المصدر. تعتبر مكتبة Python الخاصة بنا حلاً احترافيًا لحفظ XML كملفات MD عبر الإنترنت. يوفر Cloud SDK للمطورين Python وظائف قوية وإخراج MD مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Python باستخدام REST API لحفظ XML بتنسيق MD" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xml'    
    saveOptions = None
    newfilename = "Book1Saveas.md"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Python API لحفظ XML كملف MD" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>خلايا الاتصال_يحفظ_مثل_بريد_وثيقة_يحفظ_كطريقة للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Python 2.7 أو أحدث</li>
<li>Python 3.10 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
