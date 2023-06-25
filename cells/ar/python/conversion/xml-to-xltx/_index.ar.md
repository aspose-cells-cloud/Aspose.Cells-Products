---
title: تحويل XML إلى XLTX API لـ Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لتحويل ملف تنسيق XML إلى ملف بتنسيق XLTX.
url: /ar/python/conversion/xml-to-xltx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API لتحويل XML إلى XLTX" h2="Python مكتبة لتحويل XML إلى XLTX" p="استخدم Cells Conversion REST API لإنشاء مهام سير عمل جداول بيانات مخصصة في Python. هذا حل احترافي لتحويل XML إلى XLTX وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Python." urlsection="conversion/xml-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف XML إلى XLTX في Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من XML إلى XLTX مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XML إلى XLTX بواسطة Python SDK مع الحفاظ على المحتوى البنيوي والمنطقي الرئيسي لجدول بيانات XML المصدر. تعد مكتبتنا Python حلاً احترافيًا لتحويل ملفات XML إلى ملفات XLTX عبر الإنترنت. يوفر Cloud SDK للمطورين Python وظائف قوية وإخراج XLTX مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Python باستخدام REST API لتحويل XML إلى تنسيق XLTX" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xml",format="xltx")
    shutil.move(file1, "destFile.xltx")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Python API لتحويل XML إلى XLTX" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>خلايا الاتصال_دفتر العمل_يضع_يتحول_طريقة المصنف للحصول على الدفق الناتج</li>
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
