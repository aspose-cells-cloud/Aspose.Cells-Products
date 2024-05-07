---
title:  Konvertera SXC till WMF med Go
description:  Använda Aspose.Cells Cloud SDK för Go för att konvertera en fil i SXC-format till en fil i WMF-format.
kwords: Excel, Convert SXC to WMF, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert SXC to WMF using the Cells Cloud Go library.","description": "How to convert SXC to WMF using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/conversion/sxc-to-wmf/","step": [{ "@type": "HowToStep","name": "How to convert SXC to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/sxc-to-wmf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert SXC to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/sxc-to-wmf/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert SXC to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/sxc-to-wmf/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to convert SXC to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/sxc-to-wmf/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera SXC till WMF" h2="Gå bibliotek för att konvertera SXC till WMF" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Go-projekt. Detta är en professionell lösning för att konvertera SXC till WMF och andra dokumentformat online med Go." urlsection="conversion/sxc-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera SXC till WMF med Cells Cloud SDK för Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från SXC till WMF kan vara en komplex uppgift. Vår Go SDK hanterar alla konverteringar av SXC till WMF-format samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket för SXC bevaras. Vårt Go-bibliotek tillhandahåller en professionell lösning för att konvertera SXC till WMF-filer online. Denna Cloud SDK ger Go-utvecklare kraftfull funktionalitet och säkerställer WMF-utdata av hög kvalitet.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go Code Exempel för att konvertera SXC till WMF med Cells Cloud SDK" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.sxc")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "wmf"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.wmf")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man konverterar SXC till WMF med hjälp av Cells Cloud Go-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Go-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen på gång.</li>
<li>Använd metoden `PutConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>go version go1.13.0 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
