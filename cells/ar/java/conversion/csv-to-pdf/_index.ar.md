---
title:  تحويل CSV إلى PDF باستخدام Java
description:  استخدام Aspose.Cells Cloud SDK for Java لتحويل ملف بتنسيق CSV إلى ملف بتنسيق PDF.
kwords: Excel, Convert CSV to PDF, REST, Java
howto: How to convert CSV to PDF using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل CSV إلى PDF" h2="مكتبة Java لتحويل CSV إلى PDF" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Java. يعد هذا حلاً احترافيًا لتحويل ملف CSV إلى PDF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Java." urlsection="conversion/csv-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل CSV إلى PDF باستخدام Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من CSV إلى PDF مهمة معقدة. يتعامل SDK Java الخاص بنا مع جميع تحويلات تنسيق CSV إلى PDF مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات CSV المصدر. توفر مكتبتنا Java حلاً احترافيًا لتحويل ملفات CSV إلى PDF عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Java بوظائف قوية ويضمن إخراج PDF عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java مثال على الكود لتحويل CSV إلى PDF باستخدام Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.csv";
            String format = "pdf";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.pdf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية تحويل CSV إلى PDF باستخدام مكتبة Cells Cloud Java." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Java وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Java.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Maven 2.2.0 أو أحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
