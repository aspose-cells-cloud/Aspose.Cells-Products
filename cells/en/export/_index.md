---
title: Export objects of Excel 
description: Aspose.Cells Cloud REST API facilitates exporting workbooks and their internal objects to various formats and provides SDKs for multiple programming languages, including Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby, and Swift. 

---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Export objects of Excel" h2="Aspose.Cells Cloud SDK supports exporting workbooks and internal objects to over 30 file formats." p="Aspose.Cells Cloud REST API facilitates exporting workbooks and their internal objects to various formats and provides SDKs for multiple programming languages, including Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby, and Swift." urlsection="" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST  apiname="Export" %}}
{{< /blocks/products/pf/agp/feature-section >}}  
{{< blocks/products/cells/cells-cloud-api-template btName="Export" OutResultType="Variable" OutResultDataType="Class" ResultPosition="result" apireferenceurl= https://reference.aspose.cloud/cells/#/DataProcessing/PostExport >}}  
{{< blocks/products/cells/cells-cloud-upload>}}  
	{{< blocks/products/cells/cells-cloud-parameters itName="format"  required="true" prompt="Please enter format">}}
	{{< blocks/products/cells/cells-cloud-parameters itName="objectType"  required="true" prompt="Please enter objectType">}}
{{% blocks/products/cells/cells-cloud-showcode itName="streamformat" ptName="stream Format:" prompt="Please enter stream Format" %}}  
               
```cs

	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Request;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	string filePath = "test.txt";
	PostExportRequest request = new PostExportRequest();
	request.File = new Dictionary<string, Stream>();
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
    request.format = "xps";
	request.objectType = "Background";
	Aspose.Cells.Cloud.SDK.Model.FilesResult result = cellsApi.PostExport(request);
	fileStream.Close();    
	    
```     
{{% /blocks/products/cells/cells-cloud-showcode  %}}   
{{< /blocks/products/cells/cells-cloud-api-template >}}      
 

	{{< blocks/products/pf/product-card-row title="Supported File Formats" >}}
	<div class="diagram1 d2  d1-cloud">
	<div class="d1-row">
	<div class="d1-col d1-left"><header><i class="fa fa-mail-forward"> </i> Input Format</header><ul>
	<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>OpenOffice:</b> Ods, Fods, Ots</li>
	<li><b>Xml:</b>SpreadsheetML, Xml</li>
	<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>Web:</b> Html, Mhtml</li>
	</ul></div>
	<div class="d1-col d1-right"><header><i class="fa fa-mail-forward"> </i> Output Format</header><ul>
	<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Microsoft Word/PowerPoint:</b> Docx, Pptx</li>
	<li><b>OpenOffice:</b> Ods, Fods, Ots</li>
	<li><b>Xml:</b>SpreadsheetML, Xml</li>
	<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>Web:</b> Html, Mhtml</li>
	<li><b>Images:</b> Png, Jpg, Gif, Emf, Svg, Tiff</li>
	<li><b>Other:</b> Pdf, Xps, Dif, Json, Markdown, Sql</li>
	</ul></div>
	</div>
	<div class="d1-logo"><img src="/product-logos/aspose_cells-for-cloud.svg" alt="Conversion SDK"><header>Aspose.Cells</header><footer>Cloud SDK</footer></div>
	</div>
	{{< /blocks/products/pf/product-card-row >}}
{{< blocks/products/pf/product-card-row title="Popular Operates" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Export workbook to Pdf" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/export/workbook-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Go" title="Export workbook to Json" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/go/export/workbook-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Java" title="Export list object to Csv" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/java/export/listobject-to-csv/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for PHP" title="Export Chart to Png" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/php/export/chart-to-png/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Export workbook to MD" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/export/workbook-to-md/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Swift" title="Export Sheet to pdf" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/swift/export/worksheet-to-pdf/" >}}
{{< /blocks/products/pf/product-card-row >}}

{{< blocks/products/pf/product-card-row title="Supported Develop Languages" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Android" imgSrc="/cells/sdk/aspose_cells-for-android.png" productLink="/cells/android/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Go" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Net" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Node" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Ruby" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Swift" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/pf/product-card-row >}}


{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Cells Cloud SDK for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="Security" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}
