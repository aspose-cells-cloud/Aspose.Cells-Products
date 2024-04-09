---
title:  تحويل المواد المستنفدة للأوزون إلى SQL باستخدام Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لتحويل ملف تنسيق ODS إلى ملف تنسيق SQL.
kwords: Excel, Convert ODS to SQL, REST, Python
howto: How to convert ODS to SQL using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل المواد المستنفدة للأوزون إلى SQL" h2="Python مكتبة لتحويل ODS إلى SQL" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Python. يعد هذا حلاً احترافيًا لتحويل ODS إلى SQL وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Python." urlsection="conversion/ods-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل ODS إلى SQL باستخدام Cells Cloud SDK لـ Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من ODS إلى SQL مهمة معقدة. يتعامل SDK Python الخاص بنا مع جميع تحويلات تنسيق ODS إلى SQL مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات ODS المصدر. توفر مكتبتنا Python حلاً احترافيًا لتحويل ملفات ODS إلى ملفات SQL عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Python من الحصول على وظائف قوية ويضمن إخراج SQL عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python مثال على الكود لتحويل ODS إلى SQL باستخدام Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.ods",format="sql")
    shutil.move(file1, "destFile.sql")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية تحويل ODS إلى SQL باستخدام مكتبة Cells Cloud Python." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Python وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Python.</li>
<li>استخدم طريقة `put_convert_workbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Python 2.7 أو أحدث</li>
<li>Python 3.10 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
