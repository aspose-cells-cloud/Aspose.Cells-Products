---
title:  تحويل HTML إلى XLT باستخدام Android
description:  استخدام Aspose.Cells Cloud SDK لنظام Android لتحويل ملف بتنسيق HTML إلى ملف بتنسيق XLT.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل HTML إلى XLT" h2="مكتبة Android لتحويل HTML إلى XLT" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Android. يعد هذا حلاً احترافيًا لتحويل HTML إلى XLT وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Android." urlsection="conversion/html-to-xlt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل HTML إلى XLT باستخدام Cells Cloud SDK لنظام Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من HTML إلى XLT مهمة معقدة. يتعامل Android SDK الخاص بنا مع جميع تحويلات تنسيق HTML إلى XLT مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات HTML المصدر. توفر مكتبة Android الخاصة بنا حلاً احترافيًا لتحويل ملفات HTML إلى ملفات XLT عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Android من الحصول على وظائف قوية ويضمن إخراج XLT عالي الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على رمز Android لتحويل HTML إلى XLT باستخدام Cells Cloud SDK" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.html";
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
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لنظام Android لتحويل ملفات Excel إلى تنسيقات أخرى HTML إلى XLT" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>أندرويد 7 أو الأحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
