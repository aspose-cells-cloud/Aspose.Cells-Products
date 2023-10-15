---
title:  C#'i kullanarak XLS'yi FODS'ye dönüştürün
description:  XLS formatındaki bir dosyayı FODS formatındaki bir dosyaya dönüştürmek için C# için Aspose.Cells Cloud SDK'yı kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLS\'yi FODS\'ye dönüştür" h2="XLS\'yi FODS\'ye dönüştürmek için C# kütüphane" p="Net projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, C#\'i kullanarak XLS\'yi FODS\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xls-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="C# için Cells Cloud SDK\'yı kullanarak XLS\'yi FODS\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLS'den FODS'ye dönüştürmek karmaşık bir iş olabilir. C# SDK'mız, kaynak XLS elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm XLS'den FODS formatına dönüşümleri gerçekleştirir. C# kitaplığımız, XLS'yi çevrimiçi olarak FODS dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, C# geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli FODS çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Cells Bulut SDK\'yı kullanarak XLS\'yi FODS\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xls";
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
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını XLS\'den FODS\'ye diğer formatlara dönüştürmek için Cells Cloud SDK for Net nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `PutConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standardı 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
