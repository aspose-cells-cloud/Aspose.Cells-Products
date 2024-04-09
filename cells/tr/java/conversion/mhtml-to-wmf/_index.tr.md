---
title:  Java'i kullanarak MHTML'yi WMF'ye dönüştürün
description: MHTML formatındaki bir dosyayı WMF formatındaki bir dosyaya dönüştürmek için Aspose.Cells Cloud SDK for Java'i kullanma.
kwords: Excel, Convert MHTML to WMF, REST, Java
howto: How to convert MHTML to WMF using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="MHTML\'yi WMF\'ye dönüştür" h2="MHTML\'yi WMF\'ye dönüştürmek için Java kitaplığı" p="Java projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Java\'i kullanarak MHTML\'yi WMF\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/mhtml-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Cells Cloud SDK for Java\'i kullanarak MHTML\'yi WMF\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını MHTML'den WMF'ye dönüştürmek karmaşık bir iş olabilir. Java SDK'mız, kaynak MHTML elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm MHTML'den WMF formatına dönüşümleri gerçekleştirir. Java kitaplığımız, MHTML'yi çevrimiçi olarak WMF dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK'sı, Java geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli WMF çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Cells Cloud SDK\'yı kullanarak MHTML\'yi WMF\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.mhtml";
            String format = "wmf";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.wmf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Java kitaplığını kullanarak MHTML\'yi WMF\'ye nasıl dönüştüreceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>Java kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı Java'de açın.</li>
<li>Ortaya çıkan akışı almak için `putConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Maven 2.2.0 veya daha yenisi</li>
<li>Java(TM) SE Çalışma Zamanı Ortamı</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
