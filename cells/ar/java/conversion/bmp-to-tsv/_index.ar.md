---
title:  تحويل BMP إلى TSV باستخدام Java
description: استخدام Aspose.Cells Cloud SDK for Java لتحويل ملف بتنسيق BMP إلى ملف بتنسيق TSV.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل BMP إلى TSV" h2="مكتبة Java لتحويل BMP إلى TSV" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Java. يعد هذا حلاً احترافيًا لتحويل BMP إلى TSV وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Java." urlsection="conversion/bmp-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل BMP إلى TSV باستخدام Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من BMP إلى TSV مهمة معقدة. يتعامل Java SDK الخاص بنا مع جميع تحويلات تنسيق BMP إلى TSV مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات BMP المصدر. توفر مكتبتنا Java حلاً احترافيًا لتحويل BMP إلى ملفات TSV عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Java من خلال وظائف قوية ويضمن إخراج TSV عالي الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java مثال على الكود لتحويل BMP إلى TSV باستخدام Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.bmp";
            String format = "tsv";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.tsv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK for Java لتحويل ملفات Excel إلى تنسيقات أخرى BMP إلى TSV" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Maven 2.2.0 أو أحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
