---
title:  Java'i kullanarak NUMBERS'ı EMF'e dönüştürün
description:  NUMBERS biçimindeki bir dosyayı EMF biçimindeki bir dosyaya dönüştürmek için Aspose.Cells Bulut SDK'sı for Java'i kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NUMBERS\'ı EMF\'e dönüştür" h2="NUMBERS\'ı EMF\'e dönüştürmek için Java kitaplığı" p="Java projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, NUMBERS\'ı EMF\'e ve Java\'i kullanarak çevrimiçi olarak diğer belge formatlarına dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/numbers-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Cells Cloud SDK for Java\'i kullanarak NUMBERS\'ı EMF\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını NUMBERS'tan EMF'e dönüştürmek karmaşık bir iş olabilir. Java SDK'mız, kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm NUMBERS'dan EMF'e format dönüşümlerini gerçekleştirir. Java kitaplığımız, NUMBERS'ı çevrimiçi olarak EMF dosyalara dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Java geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli EMF çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java NUMBERS\'ı Cells Cloud SDK kullanarak EMF\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.numbers";
            String format = "emf";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.emf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer formatlara (NUMBERS) - EMF\'e dönüştürmek için Cells Cloud SDK for Java nasıl kullanılır?" >}}
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
