---
title:  Konvertieren Sie HTML mit PHP in TIFF
description:  Verwendung des Aspose.Cells Cloud SDK für PHP zum Konvertieren einer Datei im Format HTML in eine Datei im Format TIFF.
kwords: Excel, Convert HTML to TIFF, REST, PHP
howto: How to convert HTML to TIFF using Aspose.Cells Cloud PHP library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie HTML in TIFF" h2="PHP-Bibliothek zum Konvertieren von HTML in TIFF" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in PHP-Projekten zu erstellen. Dies ist eine professionelle Lösung, um HTML in TIFF und andere Dokumentformate online mit PHP zu konvertieren." urlsection="conversion/html-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie HTML in TIFF mit dem Cloud SDK Cells für PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von HTML in TIFF kann eine komplexe Aufgabe sein. Unser PHP SDK verarbeitet alle Formatkonvertierungen von HTML in TIFF und behält dabei den wichtigsten strukturellen und logischen Inhalt der Quelltabelle HTML bei. Unsere PHP-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von HTML- in TIFF-Dateien. Dieses Cloud SDK stellt PHP-Entwicklern leistungsstarke Funktionen zur Verfügung und gewährleistet eine qualitativ hochwertige TIFF-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Codebeispiel für die Konvertierung von HTML in TIFF mithilfe des Cloud SDK Cells" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.html';    
    $format ='tiff';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.tiff", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie HTML mithilfe der Cells Cloud PHP-Bibliothek in TIFF konvertieren." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek PHP und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in PHP.</li>
<li>Verwenden Sie die Methode `putConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>PHP 7.4 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
