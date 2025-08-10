---
title: Convert Excel files to other formats.
description: Aspose.Cells Cloud provides robust support for Excel file format conversion, a process known for its intricacy. Aspose.Cells Cloud supports 30+ file formats, including Excel, Pdf, Markdown, Json, XML, Csv, Html, and so on.
kwords: aspose cells
howto: {"@context":"https://schema.org","@type":"HowTo","name":"How to convert Excel files to other formats.","description":"Aspose.Cells Cloud provides robust support for Excel file format conversion, a process known for its intricacy. Aspose.Cells Cloud supports 30+ file formats, including Excel, Pdf, Markdown, Json, XML, Csv, Html, and so on.","image":{"@type":"ImageObject"},"url":"https://products.aspose.cloud/cells/net/conversion/","step":[{"@type":"HowToStep","name":"Install C# library","image":{"@type":"ImageObject"},"url":"https://products.aspose.cloud/cells/net/conversion/","text":"Install .NET SDK and add the reference (import the library) to your project."},{"@type":"HowToStep","name":"Read the input file using C#","image":{"@type":"ImageObject"},"url":"https://products.aspose.cloud/words/net/conversion/","text":"Open the source file in C# using REST API."},{"@type":"HowToStep","name":"Convert your file to target format","image":{"@type":"ImageObject"},"url":"https://products.aspose.cloud/cells/net/conversion/","text":"Call the PutConvertWorkbookRequest() method, passing an output filename with required extension."},{"@type":"HowToStep","name":"Get the result","image":{"@type":"ImageObject"},"url":"https://products.aspose.cloud/cells/net/conversion/","text":"Get the result of conversion as a separate file."}],"supply":{"@type":"HowToSupply","name":"document"},"tool":[{"@type":"HowToTool","name":"Visual Studio, Rider, Sublime"},{"@type":"HowToTool","name":"Aspose Cells"}],"totalTime":"PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including PDF, DOC, DOCX, ODT, RTF, HTML, Markdown, XML, PNG, JPG, TIFF, WPS, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
BreadcrumbList: {"@context":"https://schema.org","@type":"BreadcrumbList","itemListElement":[{"@type":"ListItem","item":{"@type":"Thing","@id":"https://products.aspose.cloud","name":"Products"},"position":1},{"@type":"ListItem","item":{"@type":"Thing","@id":"https://products.aspose.cloud/cells/","name":"Aspose.Cells"},"position":2},{"@type":"ListItem","item":{"@type":"Thing","@id":"https://products.aspose.cloud/cells/net/","name":".NET"},"position":3}]}
---


{{< blocks/products/pf/main-wrap-class >}}
<!-- {{< blocks/products/cells/cells-cloud-ai-assistant >}} -->


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convert Excel files to other formats" indexdesc="Aspose.Cells Cloud provides robust support for Excel file format conversion, a process known for its intricacy. Aspose.Cells Cloud supports 30+ file formats, including Excel, Pdf, Markdown, Json, XML, Csv, Html, and so on.">}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="Aspose.Cells Cloud provides REST API which supports converting Excel files to various format and offers SDKs for multiple programming languages. These programming languages are include of Net, Java, Go, NodeJS, Python, and so on. .">}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="https://api.aspose.cloud/v4.0/cells/convert/spreadsheet"  %}}

{{< blocks/products/cells/cells-cloud-api-template btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}}
{{< blocks/products/cells/cells-cloud-upload>}}

{{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers).">}}
<!-- {{< blocks/products/cells/cells-cloud-parameters itName="password"  required="False" prompt="The password needed to open an Excel file.">}}
{{< blocks/products/cells/cells-cloud-parameters itName="outPath"  required="False" prompt="Path to save the result. If it's a single file, the `outPath` should encompass both the filename and extension. In the case of multiple files, the `outPath` should only include the folder.">}}
{{< blocks/products/cells/cells-cloud-parameters itName="storageName"  required="False" prompt="The storage name where the file is situated.">}}
{{< blocks/products/cells/cells-cloud-parameters itName="checkExcelRestriction"  required="False" prompt="Whether check restriction of excel file when user modify cells related objects.">}}
{{< blocks/products/cells/cells-cloud-parameters itName="streamFormat"  required="False" prompt="The format of the input file stream. ">}}
{{< blocks/products/cells/cells-cloud-parameters itName="region"  required="False" prompt="The regional settings for workbook.">}}
{{< blocks/products/cells/cells-cloud-parameters itName="pageWideFitOnPerSheet"  required="False" prompt="The page wide fit on worksheet.">}}
{{< blocks/products/cells/cells-cloud-parameters itName="pageTallFitOnPerSheet"  required="False" prompt="The page tall fit on worksheet.">}} -->
{{< blocks/products/cells/cells-cloud-showparameters >}}
{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}

```cs
	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Model;
	using Aspose.Cells.Cloud.SDK.Request;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
    cellsApi.ConvertSpreadsheet(new ConvertSpreadsheetRequest { Spreadsheet = "EmployeeSalesSummary.xlsx", format = "pdf" }, "result.pdf");
```
{{% /blocks/products/cells/cells-cloud-showcode %}}
{{< /blocks/products/cells/cells-cloud-api-template >}}

<!-- {{< blocks/products/pf/product-card-row title="Supported File Formats" >}}
<div class="diagram1 d2  d1-cloud">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-mail-forward"> </i> Input Format</header><ul>
<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
<li><b>OpenOffice:</b> Ods, Fods, Ots</li>
<li><b>Xml:</b>SpreadsheetML, Xml</li>
<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
<li><b>Web:</b> Html, Mhtml</li>
<li><b>Images:</b> Png, Jpg, Gif, Emf</li>
<li><b>Other:</b> Pdf, Json, Markdown</li>
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
{{< /blocks/products/pf/product-card-row >}} -->

{{< blocks/products/cells/cells-cloud-available-sdks >}}


<!-- {{< blocks/products/cells/cells-cloud-resource-links >}} -->

<!-- {{< blocks/products/cells/cells-language-cloud-card-row title="Supported Develop Languages" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Go" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/">}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/">}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Net" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/">}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Node" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/">}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/">}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/">}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/">}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Ruby" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/">}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Swift" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/">}}
{{< /blocks/products/cells/cells-language-cloud-card-row >}} -->


{{< /blocks/products/pf/main-container >}}



<!-- {{< blocks/products/pf/support-learning-resources >}}
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

{{< /blocks/products/pf/support-learning-resources >}} -->

{{< blocks/products/cells/cells-cloud-resource-links >}}
{{< /blocks/products/pf/main-wrap-class >}}
