﻿---
title:  قم بتصدير LISTOBJECT إلى EMF من جدول البيانات باستخدام Python API
description:  Aspose.Cells Cloud REST API يدعم تصدير ملف Excel وكائنات داخلية لأنواع ملفات النسق. SDK يدعم أنواع لغات التطوير. وهي تشمل Android و C# و Go و Java و NodeJS و Perl و PHP و Python و Ruby و swift.
url: /ar/python/export/listobject-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API لتصدير LISTOBJECT إلى ملف EMF" h2="مكتبة Python لتصدير LISTOBJECT إلى ملف EMF" p="استخدم Cells Export REST API لتصدير مهام سير عمل العناصر الداخلية لجدول البيانات في Python. هذا حل احترافي لتصدير LISTOBJECT إلى ملف بتنسيق EMF من جدول بيانات عبر الإنترنت باستخدام Python." urlsection="export/listobject-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتصدير كائن LISTOBJECT إلى ملف بتنسيق EMF بتنسيق Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير عنصر LISTOBJECT إلى ملف EMF من جدول البيانات مهمة معقدة. تصدير LISTOBJECT إلى EMF يتم تنفيذ انتقالات تنسيق بواسطة Python SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات LISTOBJECT المصدر. تعتبر مكتبة Python الخاصة بنا حلاً احترافيًا لتصدير كائنات LISTOBJECT إلى ملفات بتنسيق EMF عبر الإنترنت. يوفر Cloud SDK للمطورين Python وظائف قوية وإخراج EMF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Python باستخدام REST API لتصدير LISTOBJECT إلى تنسيق EMF من جدول البيانات" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import base64
    from asposecellscloud.apis.light_cells_api import LightCellsApi
    cells_api = LightCellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    files ={ 
        "myDocument.xlsx" :  "c:/myDocument.xlsx",
        "Book1.xlsx" :  "c:/Book1.xlsx" 
        }
    result = cells_api.post_export(files ,"listobject","emf")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Python API لتصدير LISTOBJECT إلى EMF" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>اتصل بطريقة post_export للحصول على التدفق الناتج </li>
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