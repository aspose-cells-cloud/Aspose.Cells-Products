---
title: Exportieren Sie ARBEITSBLATT von Excel nach PDF mit Cells Cloud SDK für Ruby
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords: Excel, worksheet, pdf, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to PDF","description": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to PDF","image": {"@type": "ImageObject"},"url": "/ruby/export/worksheet-to-pdf/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to PDF step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/worksheet-to-pdf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to PDF step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/worksheet-to-pdf/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to PDF step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/worksheet-to-pdf/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie das Arbeitsblatt von Excel nach PDF" h2="Ruby-Bibliothek zum Exportieren von ARBEITSBLÄTTERN in die Datei PDF" p="Verwenden Sie Export API von Cells Cloud, um interne Objekt-Workflows aus Dateien der Datei Excel in Ruby zu exportieren. Dies ist eine professionelle Lösung, um WORKSHEET online mit Ruby aus einer Tabellenkalkulation in eine Datei im Format PDF zu exportieren." urlsection="export/worksheet-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das WORKSHEET-Objekt in eine Datei im Format PDF mit dem Cells Cloud SDK für Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren von WORKSHEET-Objekten in eine PDF-Datei aus einer Excel-Datei ist eine komplexe Aufgabe. Die Formatübergänge beim Exportieren von WORKSHEET in eine PDF-Datei werden von unserem Ruby SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quelltabelle WORKSHEET erhalten bleibt. Unsere Ruby-Bibliothek ist eine professionelle Lösung zum Online-Exportieren von WORKSHEET-Objekten in Dateien im PDF-Format. Dieses Cloud SDK bietet Ruby-Entwicklern leistungsstarke Funktionen und eine perfekte PDF-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in Ruby mit REST API zum Exportieren von WORKSHEET aus einer Tabellenkalkulation in das Format PDF" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::LiteCellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            files = {}      
            name = $DataSourceXlsx
            files[name] = ::File.open(File.expand_path("data/"+name),"r") 
            name =$AssemblyTestXlsx 
            files[name] = ::File.open(File.expand_path("data/"+name),"r")
            format = 'pdf'
            objectType =  'worksheet'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Ruby, um Objekte von Excel WORKSHEET nach PDF zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Rufen Sie die Methode post_export auf, um den resultierenden Stream zu erhalten</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Ruby 2.5 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
