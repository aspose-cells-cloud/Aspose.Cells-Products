---
title: Exportieren Sie Ods in die XLSX-Datei via PHP
description: Aspose.Cells Cloud REST API unterstützt den Export von Excel Dateien und internen Objekten in verschiedene Formatdateien. SDK unterstützt verschiedene Entwicklungssprachen. Dazu gehören Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby und Swift.
url: /de/php/export/ods-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Exportieren Sie ODS in eine XLSX-Datei in der Cloud" h2="Excel & OpenOffice-Tabellenkalkulationsexport mit Open-Source-Cloud-SDK für PHP" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=" Exportieren Sie ODS in eine XLSX-Datei im Cloud SDK für PHP" %}}
1.  Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten
1. Initialisieren Sie ```CellsApi``` mit Client-ID, Client-Geheimnis, Basis-URL und Version API
1. Rufen Sie die Methode ```cellsWorkbookPutConvertWorkBook``` auf, um den resultierenden XLSX-Stream abzurufen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Erste Schritte mit Excel REST API" %}}
 Holen Sie sich den Quellcode Excel Cloud SDK for .NET von[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) um das SDK selbst zu kompilieren oder gehen Sie zu[Veröffentlichungen](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/releases) für alternative Download-Optionen.

 Schauen Sie sich auch Swagger-basierte[API Referenz]() Erfahren Sie mehr über die[Excel RUHET API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Code für die Konvertierung von ODS in XLSX" gistPath="" %}}
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlsx';    
    $format ='xlsx';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xlsx", 'w');
    fwrite($file,$content);
    fclose($file);
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
