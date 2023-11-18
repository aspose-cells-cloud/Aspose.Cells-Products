---
title: Conversion 
description: Aspose.Cells Cloud REST API supports the conversion of excel files to different kinds of format files. SDK supports development languages. They include Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby, and swift. 

---
{{< blocks/products/pf/main-wrap-class>}}  
{{< blocks/products/cells/upper-banner h1="Conversion" h2="Aspose.Cells Cloud SDK supports file format conversion. The supported file format has more than 30+ file formats." uploadmsg="Choose file or drop file" options="HTML,jpg,XML" logoImageSrc="/cells/app-logos/aspose_cells-for-cloud.svg" pfName="Aspose.Cells Cloud" downloadUrl="" tryOnlineUrl="" >}}   

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl=https://api.aspose.cloud/v3.0/cells/convert  %}}
  
{{< /blocks/products/pf/agp/feature-section >}}  

  <div class="container" style="margin-top:30px;"> 
{{< blocks/products/cells/cells-cloud-upload>}}  

{{< blocks/products/cells/cells-cloud-parameters itName="format" ptName="Format to convert:" required="true" prompt="Please enter format">}}
{{< blocks/products/cells/cells-cloud-parameters itName="streamformat" ptName="stream Format:" required="true" prompt="Please enter stream Format">}}

 </div>                    
                  
{{% blocks/products/cells/cells-cloud-showcode itName="streamformat" ptName="stream Format:" prompt="Please enter stream Format" %}}  

                     
```cs

	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Request;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	string filePath = "test.txt";
	PutConvertWorkbookRequest request = new PutConvertWorkbookRequest();
	request.File = new Dictionary<string, Stream>();
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
	request.format = "xps";
	request.streamFormat = "html";
	Stream stream = cellsApi.PutConvertWorkbook(request);
	fileStream.Close();    
	      
``` 
{{% /blocks/products/cells/cells-cloud-showcode  %}}      
    
                         {{< blocks/products/cells/cells-cloud-button btName="Convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertWorkbook" >}}      


{{< blocks/products/cells/cells-cloud-language-card title="Supported File Formats" title2="">}}
    {{< blocks/products/cells/cells-cloud-language-cardlist title="Input Format">}}
        <li><b>Microsoft Excel:</b> XLS, XLSX, XLSB, XLSM, XLT, XLTX, XLTM</li>
        <li><b>Open Office:</b>ODS</li>
        <li><b>Extensible Markup Language:</b> XML, Josn</li>
        <li><b>Text:</b> CSV, TSV, TXT, Markdown</li>
        <li><b>Web:</b> HTML, MHTML</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}   
     {{< blocks/products/cells/cells-cloud-language-cardlist title="Output Format">}}
        <li><b>Microsoft Excel:</b> XLS, XLSX, XLSB, XLSM, XLT, XLTX, XLTM, XLAM</li>
        <li><b>Open Office:</b> ODS</li>
        <li><b>iWork Office:</b> Number</li>
        <li><b>Microsoft Office:</b> Docx, Pptx</li>
        <li><b>Extensible Markup Language:</b> XML, Josn</li>
        <li><b>Text:</b> CSV, TSV, TXT, Markdown</li>
        <li><b>Web:</b> HTML, MHTML</li>
        <li><b>Image:</b> SVG, TIFF, PNG, BMP, EMF, JPEG, GIF</li>
        <li><b>Adobe Portable Document:</b> Pdf</li>
        <li><b>Data Interchange Format:</b> Dif</li>
        <li><b>XML Paper Specification Format:</b> XPS</li>
        <li><b>Database Script:</b> SQL</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}   
{{< /blocks/products/cells/cells-cloud-language-card >}}

{{< blocks/products/cells/product-card-row title="Popular Operates" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Conversion Xlsx to Pdf" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Conversion Xlsx to Json" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Conversion Xlsx to Csv" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-csv/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Conversion Xlsx to Pdf" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Conversion Xlsx to Json" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Conversion Xlsx to Csv" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-csv/" >}}
{{< /blocks/products/cells/product-card-row >}}

{{< blocks/products/cells/product-card-row title="Supported Develop Languages" >}}
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
{{< /blocks/products/cells/product-card-row >}}


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
