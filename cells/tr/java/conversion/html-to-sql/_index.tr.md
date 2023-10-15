---
title:  HTML'i Java'i kullanarak SQL'e dönüştürün
description:  Aspose.Cells Bulut SDK for Java'i kullanarak HTML biçimindeki bir dosyayı SQL biçimindeki bir dosyaya dönüştürmek.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="HTML\'i SQL\'e dönüştür" h2="HTML\'i SQL\'e dönüştürmek için Java kitaplığı" p="Java projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, HTML\'i Java\'i kullanarak çevrimiçi olarak SQL\'e ve diğer belge formatlarına dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/html-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="HTML\'i, Cells Cloud SDK for Java\'i kullanarak SQL\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını HTML'den SQL'e dönüştürmek karmaşık bir iş olabilir. Java SDK'mız, kaynak HTML e-tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm HTML'den SQL formatına dönüşümleri gerçekleştirir. Java kitaplığımız, HTML'i çevrimiçi olarak SQL dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Java geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli SQL çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Cells Cloud SDK\'yı kullanarak HTML\'i SQL\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.html";
            String format = "sql";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.sql";
            try {
                CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
                File response = cellsApi.cellsWorkbookPutConvertWorkbook(new File(name), format, password, outPath, null,null);            
                if(response.canRead())
                {
                    if(response.exists()){
                        response.renameTo(new File(destFile));
                    }                
                }
            }
            catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer formatlara dönüştürmek için Cells Cloud SDK for Java nasıl kullanılır? HTML\'i SQL\'e dönüştürmek" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `putConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Maven 2.2.0 veya daha yenisi</li>
<li>Java(TM) SE Çalışma Zamanı Ortamı</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
