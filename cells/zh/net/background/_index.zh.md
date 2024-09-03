---
title: 为Excel文件添加文本水印并生成各种格式的输出文件。
description: 事实上，Aspose.Cells云为Excel文件添加文本水印以及生成各种格式的输出文件提供了强大的支持。
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-ai-assistant >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="为Excel文件添加文本水印并生成各种格式的输出文件。" h2="事实上，Aspose.Cells云为Excel文件添加文本水印以及生成各种格式的输出文件提供了强大的支持。" p="Aspose.Cells云提供REST API，支持为Excel文件添加文本水印并生成各种格式的输出文件，并提供多种编程语言的SDK。这些编程语言包括Net、Java、Go、NodeJS、Python等。" urlsection="" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="POST" apiurl="https://api.aspose.cloud/v3.0/cells/watermark" %}}

{{< blocks/products/cells/cells-cloud-api-template btName="RunCode" OutResultType="Variable" OutResultDataType="Class" ResponseType="FilesResult" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/#/LightCells/PostWatermark" >}}
{{< blocks/products/cells/cells-cloud-upload >}}

{{< blocks/products/cells/cells-cloud-parameters itName="text" required="True" prompt="background text." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="color" required="True" prompt="e.g. #1032ff" >}}
{{< blocks/products/cells/cells-cloud-parameters itName="outFormat" required="False" prompt="The output data file format.(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)" >}}
{{< blocks/products/cells/cells-cloud-parameters itName="password" required="False" prompt="The password needed to open an Excel file." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="checkExcelRestriction" required="False" prompt="Whether check restriction of excel file when user modify cells related objects." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="region" required="False" prompt="The regional settings for workbook." >}}
{{< blocks/products/cells/cells-cloud-showparameters >}}
{{% blocks/products/cells/cells-cloud-showcode request="text,color,outFormat,password,checkExcelRestriction,region" requestvalue=",,,,true," %}}

```cs
	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Model;
	using Aspose.Cells.Cloud.SDK.Request;
	using Newtonsoft.Json;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	var request = new PostWatermarkRequest();
	request.File = new Dictionary<string, Stream>();
	string filePath = "Book1.xlsx";
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
	request.text = "";
	request.color = "";
	request.outFormat = "";
	request.password = "";
	request.checkExcelRestriction = true;
	request.region = "";
	var result = cellsApi.PostWatermark(request);
	fileStream.Close();






```
{{% /blocks/products/cells/cells-cloud-showcode %}}
{{< /blocks/products/cells/cells-cloud-api-template >}}

{{< blocks/products/pf/product-card-row title="支持的文件格式" >}}
<div class="diagram1 d2  d1-cloud">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-mail-forward"> </i>输入格式</header><ul>
<li><b>Microsoft Excel:</b>Xls、Xlsx、Xlsb、Xlsm、Xlt、Xltx、Xltm</li>
<li><b>开发办公室：</b> Ods、Fods、Ots</li>
<li><b>XML：</b>电子表格ML、Xml</li>
<li><b>文本：</b> Csv、Tsv、Txt（制表符分隔）</li>
<li><b>网址：</b> Html、Mhtml</li>
<li><b>图片：</b> Png、Jpg、Gif、Emf</li>
<li><b>其他：</b> Pdf、Json、Markdown</li>
</ul></div>
<div class="d1-col d1-right"><header><i class="fa fa-mail-forward"> </i>输出格式</header><ul>
<li><b>Microsoft Excel:</b>Xls、Xlsx、Xlsb、Xlsm、Xlt、Xltx、Xltm</li>
<li><b>Microsoft字/PowerPoint：</b>文档、PPT</li>
<li><b>开发办公室：</b> Ods、Fods、Ots</li>
<li><b>XML：</b>电子表格ML、Xml</li>
<li><b>文本：</b> Csv、Tsv、Txt（制表符分隔）</li>
<li><b>网址：</b> Html、Mhtml</li>
<li><b>图片：</b> Png、Jpg、Gif、Emf、Svg、Tiff</li>
<li><b>其他：</b> Pdf、Xps、Dif、Json、Markdown、Sql</li>
</ul></div>
</div>
<div class="d1-logo"><img src="/product-logos/aspose_cells-for-cloud.svg" alt="Conversion SDK"><header>Aspose.Cells</header><footer>云SDK</footer></div>
</div>
{{< /blocks/products/pf/product-card-row >}}

{{< blocks/products/cells/cells-language-cloud-card-row title="支持的开发语言" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="适用于 Go 的 SDK" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="软件开发工具包 for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="网络SDK" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="节点SDK" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="红宝石 SDK" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="斯威夫特 SDK" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/cells-language-cloud-card-row >}}


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
