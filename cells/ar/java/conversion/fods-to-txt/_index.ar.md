---
title:  تحويل FODS إلى TXT في السحابة via Java
description: إنشاء أو تحرير أو تحويل ملفات Excel باستخدام REST API ومفتوح المصدر Java SDK
url: /ar/java/conversion/fods-to-txt/
family: cells
platformtag: java
feature: conversion
informat: FODS
outformat: TXT
platform: Java
otherformats: XLSB ODS XLSX CSV HTML XLTX DIF XLTM TSV XML MHTML XLSM TIFF XPS SVG FODS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل FODS إلى TXT مع Java" h2="أتمتة Excel وتحويل ملفات OpenOffice باستخدام Cloud SDK مفتوح المصدر for Java" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تحويل FODS بسيط إلى TXT" %}}
1.  قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا
1. تهيئة ```CellsApi``` بمعرف العميل وسر العميل وعنوان URL الأساسي وإصدار API
1. قم بتحميل ملف FODS إلى التخزين السحابي الافتراضي بطريقة ```CellsApi.Upload```
1. اتصل بالرقم ```CellsApi.cellsWorkbookGetWorkbook``` للحصول على ملف TXT الناتج
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ابدأ مع Excel API و Java SDK" %}}
 احصل على Excel Cloud SDK for Java كود المصدر من[جيثب](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) لتجميع SDK بنفسك أو التوجه إلى ملف[إطلاق](https://releases.aspose.cloud/) للحصول على خيارات التنزيل البديلة.

 قم أيضًا بإلقاء نظرة على المستندة إلى Swagger[API مرجع](https://apireference.aspose.cloud/cells/) لمعرفة المزيد عن[Excel الراحة API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java كود تحويل FODS إلى TXT" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "TXT";
    String folder = TEMPFOLDER;
    api.uploadFile( folder +"/"+ name, new File("c:\\TestData\\" + name) , null);
    File response = api.cellsWorkbookGetWorkbook(name, password, format, isAutoFit, onlySaveTable, folder, null, null);
}
catch (Exception e) {
    e.printStackTrace();
}
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}