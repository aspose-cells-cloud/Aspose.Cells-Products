---
title:  C#'i kullanarak PNG'i TIFF'e dönüştürün
description:  PNG biçimindeki bir dosyayı TIFF biçimindeki bir dosyaya dönüştürmek için C# için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Convert PNG to TIFF, REST, C#
howto: How to convert PNG to TIFF using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="PNG\'i TIFF\'e dönüştür" h2="PNG\'i TIFF\'e dönüştürmek için C# kitaplığı" p="Net projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, PNG\'i TIFF\'e ve diğer belge formatlarını C#\'i kullanarak çevrimiçi olarak dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/png-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="C# için Cells Cloud SDK\'yı kullanarak PNG\'i TIFF\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını PNG'den TIFF'e dönüştürmek karmaşık bir iş olabilir. C# SDK'mız, kaynak PNG elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken, PNG'den TIFF'e tüm format dönüştürmelerini gerçekleştirir. C# kitaplığımız, PNG dosyalarını çevrimiçi olarak TIFF'e dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, C# geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli TIFF çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Cells Cloud SDK\'yı kullanarak PNG\'i TIFF\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.png";
    string format = "tiff";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.tiff";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Net kitaplığını kullanarak PNG\'i TIFF\'e nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>C# kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı C#'de açın</li>
<li>Ortaya çıkan akışı almak için `PutConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standardı 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
