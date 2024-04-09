---
title:  Java'i kullanarak FODS'yi SQL'e dönüştürün
description:  FODS formatındaki bir dosyayı SQL formatındaki bir dosyaya dönüştürmek için Aspose.Cells Cloud SDK for Java'i kullanma.
kwords: Excel, Convert FODS to SQL, REST, Java
howto: How to convert FODS to SQL using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="FODS\'yi SQL\'ye dönüştür" h2="FODS\'yi SQL\'e dönüştürmek için Java kitaplığı" p="Java projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Java\'i kullanarak FODS\'yi çevrimiçi olarak SQL\'e ve diğer belge formatlarına dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/fods-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="Cells Cloud SDK for Java\'i kullanarak FODS\'yi SQL\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını FODS'den SQL'e dönüştürmek karmaşık bir iş olabilir. Java SDK'mız, kaynak FODS elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm FODS'den SQL formatına dönüşümleri gerçekleştirir. Java kitaplığımız, FODS'yi çevrimiçi olarak SQL dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Java geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli SQL çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Cells Bulut SDK\'yı kullanarak FODS\'yi SQL\'e dönüştürmek için Kod Örneği" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.fods";
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
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Java kitaplığını kullanarak FODS\'yi SQL\'e nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Java kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Java'de açın.</li>
<li>Ortaya çıkan akışı almak için `putConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Maven 2.2.0 veya daha yenisi</li>
<li>Java(TM) SE Çalışma Zamanı Ortamı</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
