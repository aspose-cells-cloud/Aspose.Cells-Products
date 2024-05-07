---
title:  Convertir GIF en SXC à l'aide de Go
description:  Utilisation du SDK Cloud Aspose.Cells pour Go pour convertir un fichier au format GIF en fichier au format SXC.
kwords: Excel, Convert GIF to SXC, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert GIF to SXC using the Cells Cloud Go library.","description": "How to convert GIF to SXC using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/conversion/gif-to-sxc/","step": [{ "@type": "HowToStep","name": "How to convert GIF to SXC using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/gif-to-sxc/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert GIF to SXC using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/gif-to-sxc/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert GIF to SXC using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/gif-to-sxc/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to convert GIF to SXC using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/gif-to-sxc/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir GIF en SXC" h2="Aller à la bibliothèque pour convertir GIF en SXC" p="Utilisez la conversion API de Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans les projets Go. Il s\'agit d\'une solution professionnelle pour convertir des GIF en SXC et d\'autres formats de documents en ligne à l\'aide de Go." urlsection="conversion/gif-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertir GIF en SXC à l\'aide du SDK Cloud Cells pour Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers GIF en SXC peut être une tâche complexe. Notre SDK Go gère toutes les conversions du format GIF au format SXC tout en préservant le contenu structurel et logique principal de la feuille de calcul GIF source. Notre bibliothèque Go fournit une solution professionnelle pour convertir des fichiers GIF en fichiers SXC en ligne. Ce SDK Cloud offre aux développeurs Go des fonctionnalités puissantes et garantit une sortie SXC de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go Exemple de code pour convertir GIF en SXC à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.gif")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "sxc"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.sxc")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment convertir GIF en SXC à l\'aide de la bibliothèque Cloud Go Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Go et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en go.</li>
<li>Utilisez la méthode `PutConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>aller à la version go1.13.0 ou plus récente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
