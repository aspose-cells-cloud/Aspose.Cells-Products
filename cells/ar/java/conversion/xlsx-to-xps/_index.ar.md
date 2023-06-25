---
title:  XLSX إلى XPS تحويل API for Java
description:  استخدام Aspose.Cells Cloud SDK for Java لتحويل ملف تنسيق XLSX إلى ملف بتنسيق XPS.
url: /ar/java/conversion/xlsx-to-xps/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API لتحويل XLSX إلى XPS" h2="مكتبة Java لتحويل XLSX إلى XPS" p="استخدم Cells Conversion REST API لإنشاء مسارات عمل جداول بيانات مخصصة في Java. هذا حل احترافي لتحويل XLSX إلى XPS وتنسيقات مستندات أخرى عبر الإنترنت باستخدام Java." urlsection="conversion/xlsx-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف XLSX إلى XPS في Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من XLSX إلى XPS مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XLSX إلى XPS بواسطة Java SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات XLSX المصدر. تعد مكتبتنا Java حلاً احترافيًا لتحويل ملفات XLSX إلى XPS عبر الإنترنت. يوفر Cloud SDK للمطورين Java وظائف قوية وإخراج XPS مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Java باستخدام REST API لتحويل XLSX إلى تنسيق XPS" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xlsx";
            String format = "xps";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xps";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Java API لتحويل XLSX إلى XPS" >}}
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
