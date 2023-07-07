---
title:  Go için MHTML'den SQL'e Dönüştürme API
description:  MHTML biçim dosyasını SQL biçim dosyasına dönüştürmek için Aspose.Cells Cloud SDK for Go'yu kullanma.
url: /tr/go/conversion/mhtml-to-sql/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="MHTML\'yi SQL\'e dönüştürmek için API\'e gidin" h2="MHTML\'yi SQL\'e dönüştürmek için kitaplığa gidin" p="Go\'da özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, MHTML\'yi Go kullanarak çevrimiçi olarak SQL\'e ve diğer belge biçimlerine dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/mhtml-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir MHTML dosyasını Go\'da SQL\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya biçimlerini MHTML'den SQL'e dönüştürmek karmaşık bir iştir. Tüm MHTML'den SQL formatına geçişler, kaynak MHTML elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken Go SDK'mız tarafından gerçekleştirilir. Go kitaplığımız, MHTML'yi çevrimiçi olarak SQL dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, Go geliştiricilerine güçlü işlevsellik ve mükemmel SQL çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="MHTML\'yi SQL formatına dönüştürmek için REST API kullanan Go\'daki kod örneği" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.mhtml")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "sql"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.sql")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="MHTML\'yi SQL\'e dönüştürmek için Go API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için CellsWorkbookPutConvertWorkbook yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>sürüm go1.13.0 veya daha yenisine gidin</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
