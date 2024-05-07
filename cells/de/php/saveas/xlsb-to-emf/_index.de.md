---
title:  Speichern Sie XLSB als EMF mit PHP
description:  Verwendung des Cloud SDK Aspose.Cells für PHP zum Speichern der Datei im XLSB-Format als Datei im Format EMF.
kwords: Excel, Save XLSB as EMF, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSB as EMF using the Cells Cloud PHP library.","description": "How to save XLSB as EMF using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/saveas/xlsb-to-emf/","step": [{ "@type": "HowToStep","name": "How to save XLSB as EMF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xlsb-to-emf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSB as EMF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xlsb-to-emf/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSB as EMF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xlsb-to-emf/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to save XLSB as EMF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xlsb-to-emf/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie XLSB unter EMF" h2="PHP Bibliothek zum Speichern von XLSB als EMF" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in PHP zu erstellen. Dies ist eine professionelle Lösung zum Speichern von XLSB als EMF und anderen Dokumentformaten online mit PHP." urlsection="saveas/xlsb-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine XLSB-Datei als EMF in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten von XLSB als EMF ist eine komplexe Aufgabe. Alle Formatübergänge von XLSB zu EMF werden von unserem PHP SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quell-XLSB-Tabelle erhalten bleibt. Unsere PHP-Bibliothek ist eine professionelle Lösung zum Online-Speichern von XLSB als EMF-Dateien. Dieses Cloud SDK bietet PHP-Entwicklern leistungsstarke Funktionen und perfekte EMF-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Codebeispiel zum Speichern von XLSB als EMF mit REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlsb';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "emf";
    $newfilename = "Book1Saveas.emf";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So speichern Sie XLSB als EMF mithilfe der Cells Cloud PHP-Bibliothek." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek PHP und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in PHP.</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>PHP 7.4 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
