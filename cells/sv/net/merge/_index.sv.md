﻿---
title: Slå samman celler i kalkylbladet.
description: Aspose.Cells Cloud ger robust stöd för att slå samman celler i kalkylbladet, en process som är känd för sin invecklade.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-ai-assistant >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Slå samman celler i kalkylbladet." h2="Aspose.Cells Cloud ger robust stöd för att slå samman celler i kalkylbladet, en process som är känd för sin invecklade." p="Aspose.Cells Cloud tillhandahåller REST API som stöder sammanslagning av celler i kalkylbladet och erbjuder SDK:er för flera programmeringsspråk. Dessa programmeringsspråk inkluderar Net, Java, Go, NodeJS, Python och så vidare." urlsection="" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="POST" apiurl="https://api.aspose.cloud/v3.0/cells/merge" %}}

{{< blocks/products/cells/cells-cloud-api-template btName="RunCode" OutResultType="Variable" OutResultDataType="Class" ResponseType="FileInfo" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/#/LightCells/PostMerge" >}}
{{< blocks/products/cells/cells-cloud-upload >}}

{{< blocks/products/cells/cells-cloud-parameters itName="outFormat" required="False" prompt="The output data file format.(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)" >}}
{{< blocks/products/cells/cells-cloud-parameters itName="mergeToOneSheet" required="False" prompt="Merge all workbooks into a sheet." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="password" required="False" prompt="The password needed to open an Excel file." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="checkExcelRestriction" required="False" prompt="Whether check restriction of excel file when user modify cells related objects." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="region" required="False" prompt="The regional settings for workbook." >}}
{{< blocks/products/cells/cells-cloud-showparameters >}}
{{% blocks/products/cells/cells-cloud-showcode request="outFormat,mergeToOneSheet,password,checkExcelRestriction,region" requestvalue=",true,,true," %}}

```cs
	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Model;
	using Aspose.Cells.Cloud.SDK.Request;
	using Newtonsoft.Json;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	var request = new PostMergeRequest();
	request.File = new Dictionary<string, Stream>();
	string filePath = "Book1.xlsx";
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
	request.outFormat = "";
	request.mergeToOneSheet = true;
	request.password = "";
	request.checkExcelRestriction = true;
	request.region = "";
	var result = cellsApi.PostMerge(request);
	fileStream.Close();





```
{{% /blocks/products/cells/cells-cloud-showcode %}}
{{< /blocks/products/cells/cells-cloud-api-template >}}

{{< blocks/products/pf/product-card-row title="Filformat som stöds" >}}
<div class="diagram1 d2  d1-cloud">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-mail-forward"> </i> Inmatningsformat</header><ul>
<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
<li><b>Öppet kontor:</b> Ods, Fods, Ots</li>
<li><b>XML:</b>SpreadsheetML, XML</li>
<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
<li><b>Webb:</b> Html, Mhtml</li>
<li><b>Bilder:</b> Png, Jpg, Gif, Emf</li>
<li><b>Övrig:</b> Pdf, Json, Markdown</li>
</ul></div>
<div class="d1-col d1-right"><header><i class="fa fa-mail-forward"> </i> Utmatningsformat</header><ul>
<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
<li><b>Microsoft Word/PowerPoint:</b> Docx, Pptx</li>
<li><b>Öppet kontor:</b> Ods, Fods, Ots</li>
<li><b>XML:</b>SpreadsheetML, XML</li>
<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
<li><b>Webb:</b> Html, Mhtml</li>
<li><b>Bilder:</b> Png, Jpg, Gif, Emf, Svg, Tiff</li>
<li><b>Övrig:</b> Pdf, Xps, Dif, Json, Markdown, Sql</li>
</ul></div>
</div>
<div class="d1-logo"><img src="/product-logos/aspose_cells-for-cloud.svg" alt="Conversion SDK"><header>Aspose.Cells</header><footer>Cloud SDK</footer></div>
</div>
{{< /blocks/products/pf/product-card-row >}}

{{< blocks/products/cells/cells-language-cloud-card-row title="Stöds utveckla språk" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Go" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Net" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Node" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Ruby" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Swift" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/cells-language-cloud-card-row >}}


{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/i18n/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Lärresurser" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Dokumentation" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="Källkod" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API Referenser" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="Handledningsvideor" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Produktsupport" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Gratis support" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="Betald support" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blogg" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Varför Aspose.Cells Cloud SDK for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Kundlista" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="säkerhet" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/i18n/support-learning-resources >}}

{{< blocks/products/pf/i18n/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}
