---
title:  Go'yu kullanarak TSV'yi TXT'ye dönüştürün
description: TSV formatındaki bir dosyayı TXT formatındaki bir dosyaya dönüştürmek için Go için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert TSV to TXT, REST, Go
howto: How to convert TSV to TXT using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="TSV\'yi TXT\'ye dönüştür" h2="TSV\'yi TXT\'ye dönüştürmek için kütüphaneye gidin" p="Go projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, Go\'yu kullanarak TSV\'yi TXT\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/tsv-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Go için Cells Cloud SDK\'yı kullanarak TSV\'yi TXT\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını TSV'den TXT'ye dönüştürmek karmaşık bir iş olabilir. Go SDK'mız, kaynak TSV e-tablosunun ana yapısal ve mantıksal içeriğini korurken tüm TSV'den TXT formatına dönüşümleri gerçekleştirir. Go kitaplığımız, TSV'yi çevrimiçi olarak TXT dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, Go geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli TXT çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Cells Bulut SDK\'yı kullanarak TSV\'yi TXT\'ye dönüştürmek için Kod Örneğine gidin" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.tsv")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "txt"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.txt")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Go kitaplığını kullanarak TSV\'yi TXT\'ye nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Go kütüphanesini kurun ve referansı projenize ekleyin (kütüphaneyi içe aktarın).</li>
<li>Kaynak dosyayı go'da açın.</li>
<li>Ortaya çıkan akışı almak için `PutConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>go sürümü go1.13.0 veya daha yeni</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
