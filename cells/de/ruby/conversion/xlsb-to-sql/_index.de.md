---
title:  Konvertieren Sie XLSB mit Ruby in SQL
description:  Verwendung des Cloud SDK Aspose.Cells für Ruby zum Konvertieren einer XLSB-Formatdatei in eine SQL-Formatdatei.
kwords: Excel, Convert XLSB to SQL, REST, Ruby
howto: How to convert XLSB to SQL using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie XLSB in SQL" h2="Ruby-Bibliothek zum Konvertieren von XLSB in SQL" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Ruby-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLSB in SQL und andere Dokumentformate mit Ruby." urlsection="conversion/xlsb-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie XLSB in SQL mit dem Cloud SDK Cells für Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLSB in SQL kann eine komplexe Aufgabe sein. Unser Ruby SDK übernimmt alle XLSB-in-SQL-Formatkonvertierungen und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLSB-Quelltabelle bei. Unsere Ruby-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLSB- in SQL-Dateien. Dieses Cloud SDK stellt Ruby-Entwicklern leistungsstarke Funktionen zur Verfügung und gewährleistet eine qualitativ hochwertige SQL-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby-Codebeispiel für die Konvertierung von XLSB in SQL mithilfe des Cloud SDK Cells" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlsb"
            format = 'sql'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie XLSB mithilfe der Cloud Ruby-Bibliothek Cells in SQL konvertieren." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Ruby-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Ruby.</li>
<li>Verwenden Sie die Methode `put_convert_workbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Ruby 2.5 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
