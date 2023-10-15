---
title:  تحويل FODS إلى XLSB via .NET
description: إنشاء أو تحرير أو تحويل ملفات Excel باستخدام Cloud API و Open Source .NET SDK
url: /ar/net/conversion/fods-to-xlsb/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: XLSB
platform: .NET
otherformats: DIF XLSX TSV XLT XLSB MD TXT XML PDF SVG ODS TIFF XPS XLTX MHTML CSV 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل FODS إلى XLSB في السحابة" h2="Excel وتحويل جداول بيانات OpenOffice باستخدام Cloud SDK مفتوح المصدر for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تحويل FODS إلى XLSB في تطبيقات .NET" %}}
1.  قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا
1. تهيئة ```CellsApi``` بمعرف العميل وسر العميل وعنوان URL الأساسي وإصدار API
1. قم بتحميل ملف FODS إلى التخزين السحابي الافتراضي بطريقة ```CellsApi.Upload```
1. اتصل بطريقة ```CellsApi.CellsSaveAsPostDocumentSaveAs``` للحصول على ملف XLSB الناتج
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ابدأ مع Excel ريست API" %}}
 احصل على Excel Cloud SDK for .NET كود المصدر من[جيثب](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) لتجميع SDK بنفسك أو التوجه إلى ملف[إطلاق](https://releases.aspose.cloud/) للحصول على خيارات التنزيل البديلة.

 قم أيضًا بإلقاء نظرة على المستندة إلى Swagger[API مرجع](https://apireference.aspose.cloud/cells/) لمعرفة المزيد عن[Excel الراحة API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET كود تحويل FODS إلى XLSB" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "xlsb";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.xlsb", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}