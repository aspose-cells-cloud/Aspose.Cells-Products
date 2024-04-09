---
title:  تحويل XLTM إلى XLT باستخدام Java
description:  استخدام Aspose.Cells Cloud SDK for Java لتحويل ملف بتنسيق XLTM إلى ملف بتنسيق XLT.
kwords: Excel, Convert XLTM to XLT, REST, Java
howto: How to convert XLTM to XLT using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل XLTM إلى XLT" h2="Java مكتبة لتحويل XLTM إلى XLT" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Java. يعد هذا حلاً احترافيًا لتحويل XLTM إلى XLT وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Java." urlsection="conversion/xltm-to-xlt/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل XLTM إلى XLT باستخدام Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLTM إلى XLT مهمة معقدة. يتعامل SDK Java الخاص بنا مع جميع تحويلات تنسيق XLTM إلى XLT مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLTM المصدر. توفر مكتبتنا Java حلاً احترافيًا لتحويل ملفات XLTM إلى XLT عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Java من الحصول على وظائف قوية ويضمن إخراج XLT عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java مثال على الكود لتحويل XLTM إلى XLT باستخدام Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xltm";
            String format = "xlt";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xlt";
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
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية تحويل XLTM إلى XLT باستخدام مكتبة Cells Cloud Java." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Java وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Java.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Maven 2.2.0 أو أحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
