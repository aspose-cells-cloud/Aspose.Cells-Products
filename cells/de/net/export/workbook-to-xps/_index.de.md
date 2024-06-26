---
title:  Exportieren Sie WORKBOOK von Excel nach XPS mit dem Cloud SDK Cells für C#
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords: Excel, workbook, xps, Net
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKBOOK to XPS","description": "How to use Cells Cloud SDK for Net to export objects from Excel WORKBOOK to XPS","image": {"@type": "ImageObject"},"url": "/net/export/workbook-to-xps/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKBOOK to XPS step 1", "image": {"@type": "ImageObject",},"url": "/net/export/workbook-to-xps/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKBOOK to XPS step 1", "image": {"@type": "ImageObject",},"url": "/net/export/workbook-to-xps/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKBOOK to XPS step 1", "image": {"@type": "ImageObject",},"url": "/net/export/workbook-to-xps/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider "},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie die Arbeitsmappe von Excel nach XPS" h2="C# Bibliothek zum Exportieren von WORKBOOK in eine XPS Datei" p="Verwenden Sie Export API von Cells Cloud, um interne Objektworkflows der Datei Excel in Net zu exportieren. Dies ist eine professionelle Lösung zum Exportieren einer Arbeitsmappe in das Format XPS aus einer Tabellenkalkulation online mit C#." urlsection="export/workbook-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das WORKBOOK-Objekt in die Formatdatei XPS mit dem Cloud SDK Cells für C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren von WORKBOOK-Objekten in eine XPS-Datei aus einer Excel-Datei ist eine komplexe Aufgabe. Der Export von WORKBOOK in eine XPS-Formatübergänge wird von unserem C#-SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quell-WORKBOOK-Tabelle erhalten bleibt. Unsere C#-Bibliothek ist eine professionelle Lösung zum Online-Exportieren von WORKBOOK-Objekten in XPS-Formatdateien. Dieses Cloud-SDK bietet C#-Entwicklern leistungsstarke Funktionen und perfekte XPS-Ausgaben.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in C# mit REST API zum Exportieren von WORKBOOK in das XPS-Format aus der Tabellenkalkulation" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "xps";
    string objectType ="workbook";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK for Net, um Objekte von Excel WORKBOOK nach XPS zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `postExport`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>NET Framework 4.5.2 oder neuer</li>
<li>Net Standard 2.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
