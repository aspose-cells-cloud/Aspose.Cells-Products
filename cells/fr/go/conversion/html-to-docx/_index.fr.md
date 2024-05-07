---
title:  Convertir HTML en DOCX à l'aide de Go
description:  Utilisation du SDK Cloud Aspose.Cells pour Go pour convertir un fichier au format HTML en fichier au format DOCX.
kwords: Excel, Convert HTML to DOCX, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert HTML to DOCX using the Cells Cloud Go library.","description": "How to convert HTML to DOCX using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/conversion/html-to-docx/","step": [{ "@type": "HowToStep","name": "How to convert HTML to DOCX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/html-to-docx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert HTML to DOCX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/html-to-docx/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert HTML to DOCX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/html-to-docx/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to convert HTML to DOCX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/html-to-docx/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir HTML en DOCX" h2="Accédez à la bibliothèque pour convertir HTML en DOCX" p="Utilisez la conversion API de Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans les projets Go. Il s\'agit d\'une solution professionnelle pour convertir HTML en DOCX et d\'autres formats de documents en ligne à l\'aide de Go." urlsection="conversion/html-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez HTML en DOCX à l\'aide du SDK Cloud Cells pour Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de HTML en DOCX peut être une tâche complexe. Notre SDK Go gère toutes les conversions du format HTML au format DOCX tout en préservant le contenu structurel et logique principal de la feuille de calcul source HTML. Notre bibliothèque Go fournit une solution professionnelle pour convertir en ligne HTML en fichiers DOCX. Ce SDK Cloud offre aux développeurs Go des fonctionnalités puissantes et garantit une sortie DOCX de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go Exemple de code pour convertir HTML en DOCX à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.html")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "docx"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.docx")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment convertir HTML en DOCX à l\'aide de la bibliothèque Cells Cloud Go." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Go et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en go.</li>
<li>Utilisez la méthode `PutConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>aller à la version go1.13.0 ou plus récente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
