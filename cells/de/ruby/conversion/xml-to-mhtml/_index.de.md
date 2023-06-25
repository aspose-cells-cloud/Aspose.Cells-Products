---
title:  XML zu MHTML Konvertieren API für Ruby
description:  Verwenden von Aspose.Cells Cloud SDK für Ruby zum Konvertieren einer XML-Formatdatei in eine MHTML-Formatdatei.
url: /de/ruby/conversion/xml-to-mhtml/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API zum Konvertieren von XML in MHTML" h2="Ruby-Bibliothek zum Konvertieren von XML in MHTML" p="Verwenden Sie Cells Conversion REST API, um benutzerdefinierte Tabellenkalkulations-Workflows in Ruby zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XML in MHTML und andere Dokumentformate mit Ruby." urlsection="conversion/xml-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie eine XML-Datei in Ruby in MHTML" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XML in MHTML ist eine komplexe Aufgabe. Alle XML-zu-MHTML-Formatübergänge werden von unserem Ruby SDK durchgeführt, während der strukturelle und logische Hauptinhalt der XML-Quelltabelle erhalten bleibt. Unsere Ruby-Bibliothek ist eine professionelle Lösung zum Online-Konvertieren von XML- in MHTML-Dateien. Dieses Cloud SDK bietet Ruby-Entwicklern leistungsstarke Funktionalität und perfekte MHTML-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in Ruby mit REST API zum Konvertieren von XML in das MHTML-Format" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xml"
            format = 'mhtml'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Ruby API zum Konvertieren von XML in MHTML" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und Version API</li>
<li>Rufzellen_Arbeitsmappe_setzen_Konvertieren_Arbeitsmappenmethode, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Ruby 2.5 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
