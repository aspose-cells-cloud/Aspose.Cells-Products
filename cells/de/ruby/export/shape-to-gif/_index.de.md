---
title:  Exportieren Sie SHAPE in GIF von Excel mit Cells Cloud SDK für Ruby
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie SHAPE von Excel in GIF" h2="Ruby-Bibliothek zum Exportieren von SHAPE in eine GIF-Datei" p="Verwenden Sie Export API von Cells Cloud, um interne Objektworkflows der Datei Excel in Ruby zu exportieren. Dies ist eine professionelle Lösung, um SHAPE online mit Ruby aus einer Tabellenkalkulation in eine GIF-Formatdatei zu exportieren." urlsection="export/shape-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das SHAPE-Objekt mit dem Cloud SDK für Ruby Cells in eine GIF-Formatdatei" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines SHAPE-Objekts aus der Datei Excel in eine GIF-Datei ist eine komplexe Aufgabe. Der Export von Übergängen von SHAPE in das GIF-Format wird von unserem Ruby SDK durchgeführt, während der strukturelle und logische Hauptinhalt der Quell-SHAPE-Tabelle erhalten bleibt. Unsere Ruby-Bibliothek ist eine professionelle Lösung zum Online-Export von SHAPE-Objekten in Dateien im GIF-Format. Dieses Cloud SDK bietet Ruby-Entwicklern leistungsstarke Funktionen und eine perfekte GIF-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in Ruby mit REST API zum Exportieren von SHAPE in das GIF-Format aus einer Tabellenkalkulation" gistPath="" %}}
  
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
            format = 'gif'
            objectType =  'shape'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Ruby, um Objekte von Excel SHAPE nach GIF zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Rufen Sie die Methode post_export auf, um den resultierenden Stream zu erhalten</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Ruby 2.5 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
