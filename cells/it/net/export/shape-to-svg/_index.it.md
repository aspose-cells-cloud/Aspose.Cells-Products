---
title:  Esporta SHAPE in SVG da Excel utilizzando Cells Cloud SDK per C#
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
kwords: Excel, shape, svg, Net
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Net to export objects from Excel SHAPE to SVG","description": "How to use Cells Cloud SDK for Net to export objects from Excel SHAPE to SVG","image": {"@type": "ImageObject"},"url": "/net/export/shape-to-svg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel SHAPE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/net/export/shape-to-svg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel SHAPE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/net/export/shape-to-svg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel SHAPE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/net/export/shape-to-svg/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider "},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Esporta SHAPE a SVG da Excel" h2="Libreria C# per esportare SHAPE nel file SVG" p="Utilizzare Esporta API di Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in Net. Questa è una soluzione professionale per esportare SHAPE nel file in formato SVG dal foglio di calcolo online utilizzando C#." urlsection="export/shape-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Esporta l\'oggetto SHAPE nel file in formato SVG utilizzando Cells Cloud SDK per C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto SHAPE nel file SVG dal file Excel è un'attività complessa. L'esportazione di SHAPE nelle transizioni del formato SVG viene eseguita dal nostro SDK C# mantenendo il contenuto strutturale e logico principale del foglio di calcolo SHAPE di origine. La nostra libreria C# è una soluzione professionale per esportare oggetti SHAPE in file in formato SVG online. Questo Cloud SDK offre agli sviluppatori C# funzionalità potenti e un output SVG perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice in C# utilizzando REST API per esportare SHAPE nel formato SVG dal foglio di calcolo" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "svg";
    string objectType ="shape";
    LightCellsApi lightCellsApi =
        new LightCellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    IDictionary<string ,Stream> files = new  Dictionary<string ,Stream>();
    files.Add("Book1.xlsx" , File.OpenRead("Book1.xlsx"));
    files.Add("myDocument.xlsx", File.OpenRead("myDocument.xlsx"));
    var filesResult = lightCellsApi.PostExport(files, objectType, format);
    foreach (var file in filesResult.Files)
    {
        string v = file.FileContent;
        string filename = file.Filename;
        byte[] workbookData = System.Convert.FromBase64String(v);
        MemoryStream memoryStream = new MemoryStream(workbookData, 0, workbookData.Length);
        memoryStream.Seek(0, SeekOrigin.Begin);
        using (FileStream fileStream = File.Create( filename))
        {
            fileStream.Position = 0;
            memoryStream.CopyTo(fileStream);
            fileStream.Close();
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK for Net per esportare oggetti da Excel SHAPE a SVG" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `postExport` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>NET Framework 4.5.2 o successiva</li>
<li>Net Standard 2.0 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
