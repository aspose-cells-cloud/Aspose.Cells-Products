---
title: Export WORKBOOK to WMF from Excel using Cells Cloud SDK for Java  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: Excel, workbook, wmf, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Java to export objects from Excel WORKBOOK to WMF","description": "How to use Cells Cloud SDK for Java to export objects from Excel WORKBOOK to WMF","image": {"@type": "ImageObject"},"url": "/java/export/workbook-to-wmf/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel WORKBOOK to WMF step 1", "image": {"@type": "ImageObject",},"url": "/java/export/workbook-to-wmf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel WORKBOOK to WMF step 1", "image": {"@type": "ImageObject",},"url": "/java/export/workbook-to-wmf/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel WORKBOOK to WMF step 1", "image": {"@type": "ImageObject",},"url": "/java/export/workbook-to-wmf/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Export WORKBOOK to WMF from Excel" h2="Java library for exporting WORKBOOK to WMF file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in Java. This is a professional solution to export WORKBOOK to WMF format file from spreadsheet online using Java." urlsection="export/workbook-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export WORKBOOK object to WMF format file using Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export WORKBOOK object to WMF file from Excel file is a complex task. Export WORKBOOK to WMF format transitions is performed by our Java SDK while maintaining the source WORKBOOK spreadsheet's main structural and logical content. Our Java library is a professional solution to export WORKBOOK objects to WMF format files online. This Cloud SDK gives Java developers powerful functionality and perfect WMF output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in Java using REST API to export WORKBOOK to WMF format from spreadsheet" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.*;
    import java.util.HashMap;
    import java.util.List;
    import java.util.Base64;
    import com.aspose.cloud.cells.api.*;
    import com.aspose.cloud.cells.model.*;
    public class Export {
        public static void main(String[] args) {
            String format = "wmf";
            String objectType = "workbook";
            HashMap<String,File> fileMap = new HashMap<String,File>();
            fileMap.put("Book1.xlsx" ,new File("C:\Book1.xlsx") );
            fileMap.put("myDocument.xlsx" ,new File("C:\myDocument.xlsx") );
            try {
                LightCellsApi cellsApi = new LightCellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"),"v3.0","https://api.aspose.cloud");
                FilesResult response = cellsApi.postExport(fileMap,objectType, format,null);            
                List<FileInfo> files = response.getFiles();
                String filename = files.get(0).getFilename();
                String fileContent = files.get(0).getFileContent();
                byte[] data = Base64.getDecoder().decode(fileContent);
                OutputStream outputStream = new FileOutputStream(filename);
                outputStream.write(data,0,data.length);
                outputStream.close();
            }catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Java to export objects from Excel WORKBOOK to WMF" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Use the `postExport` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Maven 2.2.0 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
