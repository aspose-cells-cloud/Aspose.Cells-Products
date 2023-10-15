---
title:  تحويل FODS إلى SXC على أندرويد
description: أتمتة عمليات معالجة الملفات Excel مثل الإنشاء والتحرير والتحويل باستخدام Cloud API وAndroid SDK مفتوح المصدر
url: /ar/android/conversion/fods-to-sxc/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: SXC
platform: Android
otherformats: XLSB DIF XLSX CSV XLTM SVG FODS XML TXT MD XPS HTML TIFF TSV PDF XLSM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل FODS إلى SXC في السحابة" h2="قم بتحويل Excel وجداول بيانات OpenOffice باستخدام Cloud SDK مفتوح المصدر لنظام Android" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تحويل FODS إلى SXC في تطبيقات Android" %}}
1.  قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا
1. تهيئة ```CellsApi``` بمعرف العميل وسر العميل وعنوان URL الأساسي وإصدار API
1. قم بتحميل ملف FODS إلى التخزين السحابي الافتراضي بطريقة ```CellsApiUtil.Upload```
1. اتصل بالرقم ```CellsApi.cellsWorkbookGetWorkbook``` للحصول على ملف SXC الناتج
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ابدأ مع Excel ريست API" %}}
 احصل على Excel Cloud SDK لكود مصدر ANDROID من[جيثب](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) لتجميع SDK بنفسك أو التوجه إلى ملف[إطلاق](https://releases.aspose.cloud/) للحصول على خيارات التنزيل البديلة.

 قم أيضًا بإلقاء نظرة على المستندة إلى Swagger[API مرجع](https://apireference.aspose.cloud/cells/) لمعرفة المزيد عن[Excel الراحة API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android: تحويل FODS إلى SXC" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "SXC";
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