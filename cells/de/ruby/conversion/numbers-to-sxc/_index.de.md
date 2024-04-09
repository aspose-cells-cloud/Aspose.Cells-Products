---
title:  Konvertieren Sie NUMBERS mit Ruby in SXC
description:  Verwendung des Cloud SDK Aspose.Cells für Ruby zum Konvertieren einer Datei im NUMBERS-Format in eine Datei im SXC-Format.
kwords: Excel, Convert NUMBERS to SXC, REST, Ruby
howto: How to convert NUMBERS to SXC using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie NUMBERS in SXC" h2="Ruby-Bibliothek zum Konvertieren von NUMBERS in SXC" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Ruby-Projekten zu erstellen. Dies ist eine professionelle Lösung, um NUMBERS online mit Ruby in SXC und andere Dokumentformate zu konvertieren." urlsection="conversion/numbers-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie NUMBERS mit dem Cloud SDK Cells für Ruby in SXC" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von NUMBERS in SXC kann eine komplexe Aufgabe sein. Unser Ruby SDK übernimmt alle Konvertierungen von NUMBERS in das SXC-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der NUMBERS-Quelltabelle bei. Unsere Ruby-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von NUMBERS in SXC-Dateien. Dieses Cloud SDK bietet Ruby-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige SXC-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby-Codebeispiel für die Konvertierung von NUMBERS in SXC mit dem Cloud SDK Cells" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.numbers"
            format = 'sxc'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie NUMBERS mit der Cloud Ruby-Bibliothek Cells in SXC konvertieren." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Ruby-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Ruby.</li>
<li>Verwenden Sie die Methode `put_convert_workbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Ruby 2.5 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
