---
title:  قم بتحويل FODS إلى PDF على Android
description: أتمتة Excel عمليات معالجة الملفات مثل الإنشاء والتحرير والتحويل باستخدام Cloud API و Android SDK مفتوح المصدر
url: /ar/android/conversion/fods-to-pdf/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: PDF
platform: Android
otherformats: XLSX DIF CSV XML TSV PDF MD HTML XLTX TIFF TXT FODS XLSM SVG MHTML XPS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="قم بتحويل FODS إلى PDF في السحابة" h2="قم بتحويل Excel وجداول بيانات OpenOffice باستخدام Cloud SDK مفتوح المصدر لنظام Android" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تحويل FODS إلى PDF في تطبيقات Android" %}}
1.  قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية
1. قم بتهيئة ```CellsApi``` بمعرف العميل وسر العميل وعنوان URL الأساسي وإصدار API
1. قم بتحميل ملف FODS إلى التخزين السحابي الافتراضي باستخدام طريقة ```CellsApiUtil.Upload```
1. اتصل على ```CellsApi.cellsWorkbookGetWorkbook``` للحصول على الملف الناتج PDF
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ابدأ بـ Excel REST API" %}}
 احصل على Excel Cloud SDK لكود مصدر ANDROID من[جيثب](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) لتجميع SDK بنفسك أو التوجه إلى ملف[إطلاق](https://releases.aspose.cloud/) للحصول على خيارات تنزيل بديلة.

 ألقِ نظرة أيضًا على Swagger المستندة إلى[API المرجع](https://apireference.aspose.cloud/cells/) لمعرفة المزيد عن[Excel راحة API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: تحويل FODS إلى PDF" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "PDF";
    String folder = TEMPFOLDER;
    CellsApiUtil.Upload(api, folder, name);
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