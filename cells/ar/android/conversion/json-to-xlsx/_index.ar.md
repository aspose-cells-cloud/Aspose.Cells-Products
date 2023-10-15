---
title:  تحويل JSON إلى XLSX باستخدام Android
description:  استخدام Aspose.Cells Cloud SDK لنظام Android لتحويل ملف بتنسيق JSON إلى ملف بتنسيق XLSX.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل JSON إلى XLSX" h2="مكتبة Android لتحويل JSON إلى XLSX" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Android. يعد هذا حلاً احترافيًا لتحويل JSON إلى XLSX وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Android." urlsection="conversion/json-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل JSON إلى XLSX باستخدام Cells Cloud SDK لنظام Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من JSON إلى XLSX مهمة معقدة. يتعامل Android SDK الخاص بنا مع جميع تحويلات تنسيق JSON إلى XLSX مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات JSON المصدر. توفر مكتبة Android الخاصة بنا حلاً احترافيًا لتحويل ملفات JSON إلى ملفات XLSX عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Android من الحصول على وظائف قوية ويضمن إخراج XLSX عالي الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على رمز Android لتحويل JSON إلى XLSX باستخدام Cells Cloud SDK" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.json";
                String format = "xlsx";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xlsx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لنظام Android لتحويل ملفات Excel إلى تنسيقات أخرى من JSON إلى XLSX" >}}
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
