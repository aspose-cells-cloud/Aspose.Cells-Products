---
title: Convert SXC to JSON using Java 
description: Utilizing the Aspose.Cells Cloud SDK for Java to convert a SXC format file to a JSON format file. 
kwords: Excel, Convert SXC to JSON, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert SXC to JSON using the Cells Cloud Java library.","description": "How to convert SXC to JSON using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/conversion/sxc-to-json/","step": [{ "@type": "HowToStep","name": "How to convert SXC to JSON using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/sxc-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert SXC to JSON using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/sxc-to-json/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert SXC to JSON using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/sxc-to-json/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to convert SXC to JSON using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/sxc-to-json/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert SXC to JSON" h2="Java library for converting SXC to JSON" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Java projects. This is a professional solution to convert SXC to JSON and other document formats online using Java." urlsection="conversion/sxc-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert SXC to JSON using Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v4.0/cells/convert/spreadsheet/  apireferenceurl=https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet  apimethod=PUT %}}
<br/>
Converting file formats from SXC to JSON can be a complex task. Our Java SDK handles all SXC to JSON format conversions while preserving the main structural and logical content of the source SXC spreadsheet. Our Java library provides a professional solution for converting SXC to JSON files online. This Cloud SDK empowers Java developers with powerful functionality and ensures high-quality JSON output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Code Example for converting SXC to JSON using Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    package com.aspose.cloud.cells.api;
	import com.aspose.cloud.cells.api.CellsApi;
	import com.aspose.cloud.cells.request.*;
	public class ConvertSpreadsheetExample {
        public static void main(String[] args) {
            try {
                CellsApi api = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
                ConvertSpreadsheetRequest request = new ConvertSpreadsheetRequest();
                request.setSpreadsheet("EmployeeSalesSummary.sxc");
                request.setFormat("json");
                api.convertSpreadsheet(request);
            } catch (ApiException e) {
                e.printStackTrace();
            }
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to convert SXC to JSON using the Cells Cloud Java library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Java library and add the reference (import the library) to your project.</li>
<li>Open the source file in Java.</li>
<li>Use the `putConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Maven 2.2.0 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
