---
title:  Speichern Sie die CSV-Datei unter HTML mit PHP
description:  Verwendung des Cloud SDK Aspose.Cells für PHP zum Speichern der Datei im CSV-Format als Datei im Format HTML.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="CSV unter HTML speichern" h2="PHP-Bibliothek zum Speichern von CSV als HTML" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in PHP zu erstellen. Dies ist eine professionelle Lösung, um CSV als HTML und andere Dokumentformate online mit PHP zu speichern." urlsection="saveas/csv-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine CSV-Datei unter HTML in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus CSV als HTML ist eine komplexe Aufgabe. Alle CSV-Formatübergänge in das HTML-Format werden von unserem PHP-SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quell-CSV-Tabelle erhalten bleibt. Unsere PHP-Bibliothek ist eine professionelle Lösung, um CSV als HTML-Dateien online zu speichern. Dieses Cloud SDK bietet PHP Entwicklern leistungsstarke Funktionalität und eine perfekte HTML Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP Codebeispiel zum Speichern von CSV als HTML mit REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.csv';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "html";
    $newfilename = "Book1Saveas.html";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für PHP, um Excel-Dateien in anderen CSV-Formaten als HTML zu speichern" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>PHP 7.4 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
