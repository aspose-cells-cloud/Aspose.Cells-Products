---
title:  وفر BMP كـ XLSB API مقابل Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لحفظ ملف بتنسيق BMP كملف بتنسيق XLSB.
url: /ar/python/saveas/bmp-to-xlsb/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API لحفظ BMP كـ XLSB" h2="مكتبة Python لحفظ BMP كـ XLSB" p="استخدم Cells SaveAs REST API لإنشاء مسارات عمل جداول بيانات مخصصة في Python. هذا حل احترافي لحفظ BMP كـ XLSB وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Python." urlsection="saveas/bmp-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف BMP كـ XLSB في Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من BMP كـ XLSB مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق BMP إلى XLSB بواسطة Python SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول البيانات BMP المصدر. تعد مكتبتنا Python حلاً احترافيًا لحفظ BMP كملفات XLSB عبر الإنترنت. يوفر Cloud SDK للمطورين Python وظائف قوية وإخراج XLSB مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Python باستخدام REST API لحفظ BMP بتنسيق XLSB" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.bmp'    
    saveOptions = None
    newfilename = "Book1Saveas.xlsb"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Python API لحفظ BMP كـ XLSB" >}}
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
