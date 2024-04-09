---
title:  تحويل XLTM إلى XLSB باستخدام Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لتحويل ملف تنسيق XLTM إلى ملف تنسيق XLSB.
kwords: Excel, Convert XLTM to XLSB, REST, Python
howto: How to convert XLTM to XLSB using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل XLTM إلى XLSB" h2="مكتبة Python لتحويل XLTM إلى XLSB" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Python. يعد هذا حلاً احترافيًا لتحويل XLTM إلى XLSB وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Python." urlsection="conversion/xltm-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل XLTM إلى XLSB باستخدام Cells Cloud SDK لـ Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLTM إلى XLSB مهمة معقدة. يتعامل SDK Python الخاص بنا مع جميع تحويلات تنسيق XLTM إلى XLSB مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLTM المصدر. توفر مكتبتنا Python حلاً احترافيًا لتحويل ملفات XLTM إلى ملفات XLSB عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Python من الحصول على وظائف قوية ويضمن إخراج XLSB عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python مثال على الكود لتحويل XLTM إلى XLSB باستخدام Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xltm",format="xlsb")
    shutil.move(file1, "destFile.xlsb")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية تحويل XLTM إلى XLSB باستخدام مكتبة Cells Cloud Python." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Python وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Python.</li>
<li>استخدم طريقة `put_convert_workbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Python 2.7 أو أحدث</li>
<li>Python 3.10 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
