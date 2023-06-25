---
title:  الأرقام إلى FODS حوّل API إلى Python
description:  استخدام Aspose.Cells Cloud SDK لـ Python لتحويل ملف تنسيق NUMBERS إلى ملف بتنسيق FODS.
url: /ar/python/conversion/numbers-to-fods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API لتحويل الأرقام إلى FODS" h2="Python مكتبة لتحويل الأرقام إلى FODS" p="استخدم Cells Conversion REST API لإنشاء مسارات عمل جداول بيانات مخصصة في Python. هذا حل احترافي لتحويل الأرقام إلى FODS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Python." urlsection="conversion/numbers-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف NUMBERS إلى FODS في Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من NUMBERS إلى FODS مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق NUMBERS إلى FODS بواسطة Python SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات NUMBERS المصدر. تعد مكتبتنا Python حلاً احترافيًا لتحويل NUMBERS إلى ملفات FODS عبر الإنترنت. يوفر Cloud SDK للمطورين Python وظائف قوية وإخراج FODS مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Python باستخدام REST API لتحويل الأرقام إلى تنسيق FODS" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.numbers",format="fods")
    shutil.move(file1, "destFile.fods")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Python API لتحويل الأرقام إلى FODS" >}}
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
