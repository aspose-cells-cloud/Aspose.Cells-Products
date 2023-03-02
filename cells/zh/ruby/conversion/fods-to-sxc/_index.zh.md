---
title: 从 Excel FODS 转换为 SXC via Ruby
description: 使用 REST API 和开源 Ruby SDK 创建、编辑或转换 Excel 文件
url: /zh/ruby/conversion/fods-to-sxc/
family: cells
platformtag: ruby
feature: conversion
informat: FODS
outformat: SXC
platform: Ruby
otherformats: XLSB SVG TIFF PDF XPS DIF XLSM XLTM ODS MHTML TSV CSV XML FODS MD XLSX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="使用 Ruby 将 FODS 转换为 SXC" h2="使用开源 Cloud SDK for Ruby 读取、编辑和导出 Excel 数据为其他格式" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 Ruby 将 FODS 转换为 SXC" %}}
1. 创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息
1. 使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 ```CellsApi```
1. 使用 ```CellsApi.upload_file``` 方法将 FODS 文件上传到默认云存储
1. 调用```CellsApi.cells_save_as_post_document_save_as```方法得到生成的SXC文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="开始使用 Excel API 和 Ruby SDK" %}}
从 获取 Excel Cloud SDK for Ruby 源代码[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby)自己编译 SDK 或前往[发布](https://releases.aspose.cloud/)替代下载选项。

也可以看看基于 Swagger 的[API 参考](https://apireference.aspose.cloud/cells/)了解更多[Excel 休息 API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="FODS 到 SXC 转换的 Ruby 代码" gistPath="" %}}
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby

require 'aspose_cells_cloud'

class Workbook
  include AsposeCellsCloud
  def initialize
    @instance =  AsposeCellsCloud::CellsApi.new($client_id, $client_secret, $api_version, $baseurl) 
  end
  
  # Convert document and save result to storage
  def post_document_save_as
    name = $BOOK1
    save_options = nil
    newfilename = 'output.sxc'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = $TEMPFOLDER
    result = @instance.upload_file( folder + "/" + name, ::File.open(File.expand_path("data/" + name), "r") {|io| io.read(io.size) })
    expect(result.uploaded.size).to  be > 0
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder + "/" + newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
  end
end

workbook = Workbook.new()
puts workbook.post_document_save_as
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}