---
title:  Speichern Sie XLTM als PPTX mit Ruby
description:  Verwendung von Aspose.Cells Cloud SDK für Ruby zum Speichern von XLTM-Formatdateien als PPTX-Formatdateien.
kwords: Excel, Save XLTM as PPTX, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLTM as PPTX using the Cells Cloud Ruby library.","description": "How to save XLTM as PPTX using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/xltm-to-pptx/","step": [{ "@type": "HowToStep","name": "How to save XLTM as PPTX using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xltm-to-pptx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLTM as PPTX using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xltm-to-pptx/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLTM as PPTX using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xltm-to-pptx/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save XLTM as PPTX using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xltm-to-pptx/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLTM als PPTX speichern" h2="Ruby-Bibliothek zum Speichern von XLTM als PPTX" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Ruby zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von XLTM als PPTX und anderen Dokumentformaten mit Ruby." urlsection="saveas/xltm-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine XLTM-Datei als PPTX in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus XLTM als PPTX ist eine komplexe Aufgabe. Alle XLTM-zu-PPTX-Formatübergänge werden von unserem Ruby SDK durchgeführt, während der strukturelle und logische Hauptinhalt der XLTM-Quelltabelle erhalten bleibt. Unsere Ruby-Bibliothek ist eine professionelle Lösung, um XLTM als PPTX-Dateien online zu speichern. Dieses Cloud SDK bietet Ruby-Entwicklern leistungsstarke Funktionalität und perfekte PPTX-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby-Codebeispiel zum Speichern von XLTM als PPTX mit REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.xltm'
    save_options = nil
    newfilename = 'Book1Saveas.pptx'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So speichern Sie XLTM als PPTX mit der Cloud Ruby-Bibliothek Cells." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Ruby-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Ruby.</li>
<li>Verwenden Sie die Methode `post_workbook_save_as`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Ruby 2.5 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
