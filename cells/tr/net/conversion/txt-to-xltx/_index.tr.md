---
title:  C#'i kullanarak TXT'yi XLTX'e dönüştürün
description:  TXT formatındaki bir dosyayı XLTX formatındaki bir dosyaya dönüştürmek için C# için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Convert TXT to XLTX, REST, C#
howto: How to convert TXT to XLTX using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="TXT\'yi XLTX\'ye dönüştür" h2="TXT\'yi XLTX\'e dönüştürmek için C# kütüphane" p="Net projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, C#\'i kullanarak TXT\'yi XLTX\'e ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/txt-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="C# için Cells Cloud SDK\'yı kullanarak TXT\'yi XLTX\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını TXT'den XLTX'e dönüştürmek karmaşık bir iş olabilir. C# SDK'mız, kaynak TXT elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm TXT'den XLTX'e format dönüşümlerini gerçekleştirir. C# kitaplığımız, TXT'yi çevrimiçi olarak XLTX dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, C# geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli XLTX çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Cells Bulut SDK\'yı kullanarak TXT\'yi XLTX\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.txt";
    string format = "xltx";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xltx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Net kitaplığını kullanarak TXT\'yi XLTX\'e nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>C# kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı C#'de açın</li>
<li>Ortaya çıkan akışı almak için `PutConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standardı 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
