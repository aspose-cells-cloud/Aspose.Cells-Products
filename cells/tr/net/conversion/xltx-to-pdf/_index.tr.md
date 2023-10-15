---
title:  C#'i kullanarak XLTX'i PDF'e dönüştürün
description:  XLTX biçimindeki bir dosyayı PDF biçimindeki bir dosyaya dönüştürmek için C# için Aspose.Cells Bulut SDK'sını kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLTX\'i PDF\'e dönüştür" h2="XLTX\'i PDF\'e dönüştürmek için C# kitaplığı" p="Net projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, XLTX\'i PDF\'e ve C#\'i kullanarak çevrimiçi olarak diğer belge formatlarına dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xltx-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="C# için Cells Cloud SDK\'yı kullanarak XLTX\'i PDF\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLTX'ten PDF'e dönüştürmek karmaşık bir iş olabilir. C# SDK'mız, kaynak XLTX elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm XLTX'ten PDF formatına dönüşümleri gerçekleştirir. C# kitaplığımız, XLTX'i çevrimiçi olarak PDF dosyalara dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, C# geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli PDF çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Cells Bulut SDK\'yı kullanarak XLTX\'i PDF\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xltx";
    string format = "pdf";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.pdf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer XLTX formatlarından PDF\'e dönüştürmek için Cells Cloud SDK for Net nasıl kullanılır?" >}}
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
