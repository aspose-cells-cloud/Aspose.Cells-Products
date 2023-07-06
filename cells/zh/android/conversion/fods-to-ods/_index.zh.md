---
title: 在 Android 上将 FODS 转换为 ODS
description: 自动化 Excel 文件操作操作，例如使用云 API 和开源 Android SDK 创建、编辑和转换
url: /zh/android/conversion/fods-to-ods/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: ODS
platform: Android
otherformats: CSV XLSB TIFF HTML FODS MD XLT XLSX SVG XLTX TSV XLSM PDF MHTML XLTM TXT 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="在云端将 FODS 转换为 ODS" h2="使用适用于 Android 的开源 Cloud SDK 转换 Excel 和 OpenOffice 电子表格" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Android 应用程序中 FODS 到 ODS 的转换" %}}
1. 创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息
1. 使用客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 ```CellsApi```
1. 使用 ```CellsApiUtil.Upload``` 方法将 FODS 文件上传到默认云存储
1. 拨打```CellsApi.cellsWorkbookGetWorkbook```获取ODS文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="开始使用 Excel REST API" %}}
获取 Excel Cloud SDK for ANDROID 源代码[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android)自己编译 SDK 或前往[发布](https://releases.aspose.cloud/)以获得替代下载选项。

另请查看基于 Swagger 的[API 参考](https://apireference.aspose.cloud/cells/)了解更多关于[Excel 休息 API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android：FODS 到 ODS 转换" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "ODS";
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