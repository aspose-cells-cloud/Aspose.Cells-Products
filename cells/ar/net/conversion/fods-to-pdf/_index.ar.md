---
title:  تحويل FODS إلى PDF via .NET
description: إنشاء ملفات Excel أو تحريرها أو تحويلها باستخدام Cloud API و Open Source .NET SDK
url: /ar/net/conversion/fods-to-pdf/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: PDF
platform: .NET
otherformats: TIFF HTML XML SVG CSV XLT DIF XLS XLTM FODS TSV PDF MD XPS XLSX XLSB 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="قم بتحويل FODS إلى PDF في السحابة" h2="Excel & تحويل جدول بيانات OpenOffice باستخدام Cloud SDK مفتوح المصدر for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تحويل FODS إلى PDF في تطبيقات .NET" %}}
1.  قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية
1. قم بتهيئة ```CellsApi``` بمعرف العميل وسر العميل وعنوان URL الأساسي وإصدار API
1. قم بتحميل ملف FODS إلى التخزين السحابي الافتراضي باستخدام طريقة ```CellsApi.Upload```
1. اتصل بالطريقة ```CellsApi.CellsSaveAsPostDocumentSaveAs``` للحصول على الملف PDF الناتج
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ابدأ بـ Excel REST API" %}}
 احصل على كود المصدر Excel Cloud SDK for .NET من[جيثب](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) لتجميع SDK بنفسك أو التوجه إلى ملف[إطلاق](https://releases.aspose.cloud/) للحصول على خيارات تنزيل بديلة.

 ألقِ نظرة أيضًا على Swagger المستندة إلى[API المرجع](https://apireference.aspose.cloud/cells/) لمعرفة المزيد عن[Excel راحة API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET كود FODS لتحويل PDF" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "pdf";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.pdf", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}