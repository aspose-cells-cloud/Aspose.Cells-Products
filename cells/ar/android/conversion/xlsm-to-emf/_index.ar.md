---
title:  تحويل XLSM إلى EMF باستخدام Android
description:  استخدام Aspose.Cells Cloud SDK لنظام Android لتحويل ملف بتنسيق XLSM إلى ملف بتنسيق EMF.
kwords: Excel, Convert XLSM to EMF, REST, Android
howto: How to convert XLSM to EMF using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل XLSM إلى EMF" h2="مكتبة Android لتحويل XLSM إلى EMF" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Android. يعد هذا حلاً احترافيًا لتحويل XLSM إلى EMF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Android." urlsection="conversion/xlsm-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل XLSM إلى EMF باستخدام Cells Cloud SDK لنظام Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLSM إلى EMF مهمة معقدة. يتعامل Android SDK الخاص بنا مع جميع تحويلات تنسيق XLSM إلى EMF مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLSM المصدر. توفر مكتبة Android الخاصة بنا حلاً احترافيًا لتحويل ملفات XLSM إلى EMF عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Android من وظائف قوية ويضمن إخراج EMF عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على رمز Android لتحويل XLSM إلى EMF باستخدام Cells Cloud SDK" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xlsm";
                String format = "emf";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.emf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لنظام Android لتحويل ملفات Excel إلى تنسيقات أخرى" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>أندرويد 7 أو الأحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
