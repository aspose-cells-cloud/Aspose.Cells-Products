---
title:  C#'i kullanarak NUMBERS'ı SVG'e dönüştürün
description:  NUMBERS biçimindeki bir dosyayı SVG biçimindeki bir dosyaya dönüştürmek için C# için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Convert NUMBERS to SVG, REST, C#
howto: How to convert NUMBERS to SVG using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="NUMBERS\'ı SVG\'e dönüştür" h2="NUMBERS\'ı SVG\'e dönüştürmek için C# kitaplığı" p="Net projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, NUMBERS\'ı SVG\'e ve C#\'i kullanarak çevrimiçi olarak diğer belge formatlarına dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/numbers-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="C# için Cells Cloud SDK\'yı kullanarak NUMBERS\'ı SVG\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını NUMBERS'tan SVG'e dönüştürmek karmaşık bir iş olabilir. C# SDK'mız, kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm NUMBERS'dan SVG'e format dönüşümlerini gerçekleştirir. C# kitaplığımız, NUMBERS'ı çevrimiçi olarak SVG dosyalara dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, C# geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli SVG çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# NUMBERS\'ı Cells Cloud SDK kullanarak SVG\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string format = "svg";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.svg";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Net kitaplığını kullanarak NUMBERS\'ı SVG\'e nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>C# kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı C#'de açın</li>
<li>Ortaya çıkan akışı almak için `PutConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standardı 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
