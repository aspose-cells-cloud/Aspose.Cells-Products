---
title:  تحويل XLTX إلى XPS باستخدام Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لتحويل ملف بتنسيق XLTX إلى ملف بتنسيق XPS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل XLTX إلى XPS" h2="مكتبة Python لتحويل XLTX إلى XPS" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Python. يعد هذا حلاً احترافيًا لتحويل XLTX إلى XPS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Python." urlsection="conversion/xltx-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل XLTX إلى XPS باستخدام Cells Cloud SDK لـ Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLTX إلى XPS مهمة معقدة. يتعامل SDK Python الخاص بنا مع جميع تحويلات تنسيق XLTX إلى XPS مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLTX المصدر. توفر مكتبتنا Python حلاً احترافيًا لتحويل ملفات XLTX إلى XPS عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Python بوظائف قوية ويضمن إخراج XPS عالي الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python مثال على الكود لتحويل XLTX إلى XPS باستخدام Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xltx",format="xps")
    shutil.move(file1, "destFile.xps")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ Python لتحويل ملفات Excel إلى تنسيقات أخرى XLTX إلى XPS" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `put_convert_workbook` لاسترداد الدفق الناتج.</li>
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
