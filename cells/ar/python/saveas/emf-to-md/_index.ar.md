---
title:  احفظ EMF كـ MD API مقابل Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لحفظ ملف بتنسيق EMF كملف بتنسيق MD.
url: /ar/python/saveas/emf-to-md/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API لحفظ EMF كـ MD" h2="مكتبة Python لحفظ EMF كـ MD" p="استخدم Cells SaveAs REST API لإنشاء مسارات عمل جداول بيانات مخصصة في Python. هذا حل احترافي لحفظ EMF كـ MD وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Python." urlsection="saveas/emf-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف EMF كملف MD في Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من EMF مثل MD مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق EMF إلى MD بواسطة Python SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول البيانات EMF المصدر. مكتبتنا Python هي حل احترافي لحفظ EMF كملفات MD عبر الإنترنت. يوفر Cloud SDK للمطورين Python وظائف قوية وإخراج MD مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Python باستخدام REST API لحفظ EMF بتنسيق MD" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.emf'    
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Python API لحفظ EMF كـ MD" >}}
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
