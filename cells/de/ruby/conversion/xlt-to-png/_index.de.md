---
title:  Konvertieren Sie XLT mit Ruby in PNG
description: Verwendung des Aspose.Cells Cloud SDK für Ruby zum Konvertieren einer Datei im XLT-Format in eine Datei im PNG-Format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie XLT in PNG" h2="Ruby-Bibliothek zum Konvertieren von XLT in PNG" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Ruby-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLT in PNG und andere Dokumentformate mit Ruby." urlsection="conversion/xlt-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie XLT in PNG mit dem Cloud SDK Cells für Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLT in PNG kann eine komplexe Aufgabe sein. Unser Ruby SDK verarbeitet alle XLT-Formatkonvertierungen in das PNG-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLT-Quelltabelle bei. Unsere Ruby-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLT- in PNG-Dateien. Dieses Cloud SDK bietet Ruby-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige PNG-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ruby-Codebeispiel für die Konvertierung von XLT in PNG mithilfe des Cloud SDK Cells" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlt"
            format = 'png'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Ruby, um Excel-Dateien in andere Formate von XLT in PNG zu konvertieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `put_convert_workbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Ruby 2.5 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
