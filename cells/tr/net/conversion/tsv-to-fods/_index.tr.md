---
title:  C#'i kullanarak TSV'yi FODS'ye dönüştürün
description:  TSV formatındaki bir dosyayı FODS formatındaki bir dosyaya dönüştürmek için C# için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert TSV to FODS, REST, C#
howto: How to convert TSV to FODS using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="TSV\'yi FODS\'ye dönüştür" h2="TSV\'yi FODS\'ye dönüştürmek için C# kütüphane" p="Net projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, C#\'i kullanarak TSV\'yi FODS\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/tsv-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="C# için Cells Cloud SDK\'yı kullanarak TSV\'yi FODS\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını TSV'den FODS'ye dönüştürmek karmaşık bir iş olabilir. C# SDK'mız, kaynak TSV elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm TSV'den FODS formatına dönüşümleri gerçekleştirir. C# kitaplığımız, TSV'yi çevrimiçi olarak FODS dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, C# geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli FODS çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Cells Bulut SDK\'yı kullanarak TSV\'yi FODS\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.tsv";
    string format = "fods";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.fods";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Net kitaplığını kullanarak TSV\'yi FODS\'ye nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>C# kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı C#'de açın</li>
<li>Ortaya çıkan akışı almak için `PutConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standardı 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
