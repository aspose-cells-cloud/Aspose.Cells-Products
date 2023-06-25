---
title:  Exportieren Sie LISTOBJECT aus der Tabelle mit Ruby API nach TIFF
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
url: /de/ruby/export/listobject-to-tiff/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API zum Exportieren von LISTOBJECT in die Datei TIFF" h2="Ruby-Bibliothek zum Exportieren von LISTOBJECT in die Datei TIFF" p="Verwenden Sie Cells Export REST API, um Arbeitsabläufe interner Tabellenkalkulationsobjekte in Ruby zu exportieren. Dies ist eine professionelle Lösung zum Exportieren von LISTOBJECT in eine Datei im Format TIFF aus einer Tabellenkalkulation online mit Ruby." urlsection="export/listobject-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportieren Sie das LISTOBJECT-Objekt in eine Datei im Format TIFF in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren des LISTOBJECT-Objekts aus der Tabellenkalkulation in die Datei TIFF ist eine komplexe Aufgabe. Der Export von LISTOBJECT-Formatübergängen in das TIFF-Format wird von unserem Ruby SDK durchgeführt, während der strukturelle und logische Hauptinhalt der Quell-LISTOBJECT-Tabelle erhalten bleibt. Unsere Ruby-Bibliothek ist eine professionelle Lösung zum Online-Export von LISTOBJECT-Objekten in Dateien im Format TIFF. Dieses Cloud SDK bietet Ruby-Entwicklern leistungsstarke Funktionalität und eine perfekte TIFF-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in Ruby mit REST API zum Exportieren von LISTOBJECT in das Format TIFF aus der Tabellenkalkulation" gistPath="" %}}
  
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
            format = 'tiff'
            objectType =  'listobject'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Ruby API, um LISTOBJECT nach TIFF zu exportieren" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und Version API</li>
<li>Rufen Sie die Methode post_export auf, um den resultierenden Stream zu erhalten</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Ruby 2.5 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
