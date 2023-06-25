---
title:  تحويل XML إلى MHTML API for Java
description:  استخدام Aspose.Cells Cloud SDK for Java لتحويل ملف تنسيق XML إلى ملف بتنسيق MHTML.
url: /ar/java/conversion/xml-to-mhtml/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API لتحويل XML إلى MHTML" h2="Java مكتبة لتحويل XML إلى MHTML" p="استخدم Cells Conversion REST API لإنشاء جداول سير عمل مخصصة لجداول البيانات في Java. هذا حل احترافي لتحويل XML إلى MHTML وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Java." urlsection="conversion/xml-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف XML إلى MHTML في Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من XML إلى MHTML مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XML إلى MHTML بواسطة Java SDK مع الحفاظ على المحتوى البنيوي والمنطقي الرئيسي لجدول بيانات XML المصدر. تعد مكتبتنا Java حلاً احترافيًا لتحويل ملفات XML إلى MHTML عبر الإنترنت. يوفر Cloud SDK للمطورين Java وظائف قوية وإخراج MHTML مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Java باستخدام REST API لتحويل XML إلى تنسيق MHTML" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xml";
            String format = "mhtml";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.mhtml";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Java API لتحويل XML إلى MHTML" >}}
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
