﻿---
title:  EMF لتحويل XLS API for Java
description:  Cloud APIs & SDKs لـ Microsoft Excel & OpenOffice Calc. تحويل جدول البيانات إلى ملف تنسيق آخر.
url: /ar/java/conversion/emf-to-xls/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API لتحويل EMF إلى XLS" h2="Java مكتبة لتحويل EMF إلى XLS" p="استخدم Cells Conversion REST API لإنشاء مسارات عمل جداول بيانات مخصصة في Java. هذا حل احترافي لتحويل EMF إلى XLS وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Java." urlsection="conversion/emf-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف EMF إلى XLS في Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من EMF إلى XLS مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق EMF إلى XLS بواسطة Java SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول البيانات EMF المصدر. تعد مكتبتنا Java حلاً احترافيًا لتحويل EMF إلى ملفات XLS عبر الإنترنت. يوفر Cloud SDK للمطورين Java وظائف قوية وإخراج XLS مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Java باستخدام REST API لتحويل EMF إلى تنسيق XLS" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.emf";
            String format = "xls";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xls";
            try {
                CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
                File response = cellsApi.cellsWorkbookPutConvertWorkbook(new File(name), format, password, outPath, null,null);            
                if(response.canRead())
                {
                    if(response.exists()){
                        response.renameTo(new File(destFile));
                    }                
                }
            }
            catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Java API لتحويل EMF إلى XLS" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة cellWorkbookPutConvertWorkbook للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Maven 2.2.0 أو أحدث</li>
<li>Java (TM) بيئة وقت التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}