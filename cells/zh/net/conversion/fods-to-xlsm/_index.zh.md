---
title: 将 FODS 转换为 XLSM via .NET
description: 使用 Cloud API 和开源 .NET SDK 创建、编辑或转换 Excel 文件
url: /zh/net/conversion/fods-to-xlsm/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: XLSM
platform: .NET
otherformats: XLS PDF FODS TSV XLSB MD XLT XML TXT XLSM SVG TIFF DIF XLSX MHTML XLTM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="在云端将 FODS 转换为 XLSM" h2="Excel & 使用开源 Cloud SDK 进行 OpenOffice 电子表格转换 for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET 应用程序中的 FODS 到 XLSM 转换" %}}
1. 创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息
1. 使用客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 ```CellsApi```
1. 使用 ```CellsApi.Upload``` 方法将 FODS 文件上传到默认云存储
1. 调用```CellsApi.CellsSaveAsPostDocumentSaveAs```方法获取生成的XLSM文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="开始使用 Excel REST API" %}}
获取 Excel Cloud SDK for .NET 源代码[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet)自己编译 SDK 或前往[发布](https://releases.aspose.cloud/)以获得替代下载选项。

另请查看基于 Swagger 的[API 参考](https://apireference.aspose.cloud/cells/)了解更多关于[Excel 休息 API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET FODS 到 XLSM 转换代码" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "xlsm";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.xlsm", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}