---
title:  تحويل HTML إلى JPG باستخدام Java
description:  استخدام Aspose.Cells Cloud SDK for Java لتحويل ملف بتنسيق HTML إلى ملف بتنسيق JPG.
kwords: Excel, Convert HTML to JPG, REST, Java
howto: How to convert HTML to JPG using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل HTML إلى JPG" h2="مكتبة Java لتحويل HTML إلى JPG" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Java. يعد هذا حلاً احترافيًا لتحويل HTML إلى JPG وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Java." urlsection="conversion/html-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل HTML إلى JPG باستخدام Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من HTML إلى JPG مهمة معقدة. يتعامل SDK Java الخاص بنا مع جميع تحويلات تنسيق HTML إلى JPG مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات HTML المصدر. توفر مكتبتنا Java حلاً احترافيًا لتحويل HTML إلى ملفات JPG عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Java من الحصول على وظائف قوية ويضمن إخراج JPG عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java مثال على الكود لتحويل HTML إلى JPG باستخدام Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.html";
            String format = "jpg";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.jpg";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية تحويل HTML إلى JPG باستخدام مكتبة Cells Cloud Java." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Java وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Java.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Maven 2.2.0 أو أحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
