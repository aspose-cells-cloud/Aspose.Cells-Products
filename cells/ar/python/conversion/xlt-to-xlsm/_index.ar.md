---
title:  XLT إلى XLSM تحويل API لـ Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لتحويل ملف تنسيق XLT إلى ملف بتنسيق XLSM.
url: /ar/python/conversion/xlt-to-xlsm/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API لتحويل XLT إلى XLSM" h2="Python مكتبة لتحويل XLT إلى XLSM" p="استخدم Cells Conversion REST API لإنشاء مهام سير عمل جداول بيانات مخصصة في Python. هذا حل احترافي لتحويل XLT إلى XLSM وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Python." urlsection="conversion/xlt-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف XLT إلى XLSM في Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من XLT إلى XLSM مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XLT إلى XLSM بواسطة Python SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات XLT المصدر. تعد مكتبتنا Python حلاً احترافيًا لتحويل ملفات XLT إلى XLSM عبر الإنترنت. يوفر Cloud SDK للمطورين Python وظائف قوية وإخراج XLSM مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Python باستخدام REST API لتحويل XLT إلى تنسيق XLSM" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlt",format="xlsm")
    shutil.move(file1, "destFile.xlsm")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Python API لتحويل XLT إلى XLSM" >}}
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
