---
title: 使用 C# 合并 Excel 文件
description: Aspose.Cells Cloud REST API支持使用C#将多个Excel文件合并为单个Excel文件，并提供各种编程语言的SDK。
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="使用 C# 合并 Excel 文件" h2="Aspose.Cells Cloud SDK 支持将多个 Excel 文件合并为单个 Excel 文件。" p="Aspose.Cells Cloud REST API支持使用C#将多个Excel文件合并为单个Excel文件，并提供各种编程语言的SDK。" urlsection="merge/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/cells/cells-cloud-api-http-method apiname="POST" apiurl="https://api.aspose.cloud/v3.0/cells/merge" %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/cells/cells-cloud-api-template btName="Merge" OutResultType="Variable" OutResultDataType="Class" ResultPosition="FileInfo" apireferenceurl="https://reference.aspose.cloud/cells/#/LightCells/PostMerge" >}}  
{{< blocks/products/cells/cells-cloud-upload >}}  
 
	{{< blocks/products/cells/cells-cloud-parameters itName="format" required="true" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}}
	{{< blocks/products/cells/cells-cloud-parameters itName="mergeToOneSheet" required="true" prompt="mergeToOneSheet" >}} 
                        
{{% blocks/products/cells/cells-cloud-showcode %}}         
 
                                    
```cs

	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Request;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	string filePath = "test.txt";
	PostMergeRequest  request = new PostMergeRequest();
	request.File = new Dictionary<string, Stream>();
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath1, fileStream1);
	request.File.Add(filePath2, fileStream2);
	request.format = "xps";
	request.mergeToOneSheet = false;


	Aspose.Cells.Cloud.SDK.Model.FileInfo fileInfo = cellsApi.PostMerge(request);
	fileStream.Close();
	      
```  
{{% /blocks/products/cells/cells-cloud-showcode %}}   
{{< /blocks/products/cells/cells-cloud-api-template >}}     

{{< blocks/products/cells/cells-cloud-language-card title="支持的文件格式" >}}
    {{< blocks/products/cells/cells-cloud-language-cardlist title="输入格式" >}}
        <li><b>Microsoft Excel:</b>Xls、Xlsx、Xlsb、Xlsm、Xlt、Xltx、Xltm</li>
	<li><b>开发办公室：</b> Ods、Fods、Ots</li>
	<li><b>XML：</b>电子表格ML、Xml</li>
	<li><b>文本：</b> Csv、Tsv、Txt（制表符分隔）</li>
	<li><b>网址：</b> Html、Mhtml</li>
	<li><b>图片：</b> Png、Jpg、Gif、Emf</li>
	<li><b>其他：</b> Pdf、Json、Markdown</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}   

    

     {{< blocks/products/cells/cells-cloud-language-cardlist title="输出格式" >}}
        <li><b>Microsoft Excel:</b>Xls、Xlsx、Xlsb、Xlsm、Xlt、Xltx、Xltm</li>
	<li><b>Microsoft字/PowerPoint：</b>文档、PPT</li>
	<li><b>开发办公室：</b> Ods、Fods、Ots</li>
	<li><b>XML：</b>电子表格ML、Xml</li>
	<li><b>文本：</b> Csv、Tsv、Txt（制表符分隔）</li>
	<li><b>网址：</b> Html、Mhtml</li>
	<li><b>图片：</b> Png、Jpg、Gif、Emf、Svg、Tiff</li>
	<li><b>其他：</b> Pdf、Xps、Dif、Json、Markdown、Sql</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}    

{{< /blocks/products/cells/cells-cloud-language-card >}}

{{< blocks/products/cells/product-card-row title="热门经营" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="合并多个Excel文件" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/merge/multi-files/" >}}
{{< /blocks/products/cells/product-card-row >}}

{{< blocks/products/cells/product-card-row title="支持的开发语言" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="安卓 SDK" imgSrc="/cells/sdk/aspose_cells-for-android.png" productLink="/cells/android/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="适用于 Go 的 SDK" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="软件开发工具包 for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="网络SDK" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="节点SDK" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="红宝石 SDK" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="斯威夫特 SDK" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/product-card-row >}}
{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/i18n/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="学习资源" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="文档" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="源代码" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API 参考文献" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="教程视频" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="产品支持" tabId="support" >}}
{{< blocks/products/pf/slr-element name="免费支持" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="付费支持" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="博客" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="为什么是Aspose.Cells云SDK for .NET？" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="客户名单" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="安全" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/i18n/support-learning-resources >}}

{{< blocks/products/pf/i18n/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}
