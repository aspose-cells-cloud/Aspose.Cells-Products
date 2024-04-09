---
title:  تحويل XLT إلى SXC باستخدام Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لتحويل ملف بتنسيق XLT إلى ملف بتنسيق SXC.
kwords: Excel, Convert XLT to SXC, REST, Python
howto: How to convert XLT to SXC using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل XLT إلى SXC" h2="مكتبة Python لتحويل XLT إلى SXC" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Python. يعد هذا حلاً احترافيًا لتحويل XLT إلى SXC وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Python." urlsection="conversion/xlt-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل XLT إلى SXC باستخدام Cells Cloud SDK لـ Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLT إلى SXC مهمة معقدة. يتعامل SDK Python الخاص بنا مع جميع تحويلات تنسيق XLT إلى SXC مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLT المصدر. توفر مكتبتنا Python حلاً احترافيًا لتحويل ملفات XLT إلى SXC عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Python من الحصول على وظائف قوية ويضمن إخراج SXC عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python مثال على الكود لتحويل XLT إلى SXC باستخدام Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlt",format="sxc")
    shutil.move(file1, "destFile.sxc")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية تحويل XLT إلى SXC باستخدام مكتبة Cells Cloud Python." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Python وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Python.</li>
<li>استخدم طريقة `put_convert_workbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Python 2.7 أو أحدث</li>
<li>Python 3.10 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
