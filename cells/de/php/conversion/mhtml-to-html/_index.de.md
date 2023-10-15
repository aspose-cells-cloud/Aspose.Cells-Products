---
title:  Konvertieren Sie MHTML mit PHP in HTML
description:  Verwendung des Aspose.Cells Cloud SDK für PHP zum Konvertieren einer Datei im MHTML-Format in eine Datei im HTML-Format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie MHTML in HTML" h2="PHP-Bibliothek zum Konvertieren von MHTML in HTML" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in PHP-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Konvertieren von MHTML in HTML und andere Dokumentformate online mit PHP." urlsection="conversion/mhtml-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie MHTML in HTML mit dem Cloud SDK Cells für PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von MHTML in HTML kann eine komplexe Aufgabe sein. Unser PHP SDK übernimmt alle Konvertierungen von MHTML in das HTML-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der Quell-MHTML-Tabelle bei. Unsere PHP-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von MHTML in HTML-Dateien. Dieses Cloud SDK bietet PHP-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige HTML-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP Codebeispiel für die Konvertierung von MHTML in HTML mit Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.mhtml';    
    $format ='html';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.html", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für PHP, um Excel-Dateien in andere Formate von MHTML in HTML zu konvertieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `putConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>PHP 7.4 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
