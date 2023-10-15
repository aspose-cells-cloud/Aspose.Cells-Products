---
title:  Java'i kullanarak XLSX'i XLSB'ye dönüştürün
description: XLSX biçimindeki bir dosyayı XLSB biçimindeki bir dosyaya dönüştürmek için Aspose.Cells Bulut SDK for Java'i kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSX\'yi XLSB\'ye dönüştür" h2="XLSX\'i XLSB\'ye dönüştürmek için Java kütüphane" p="Java projelerinde özelleştirilmiş e-tablo iş akışları oluşturmak için Cells Bulutunun API Dönüşümünü kullanın. Bu, Java numaralı telefonu kullanarak XLSX\'i XLSB\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xlsx-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Cells Cloud SDK for Java\'i kullanarak XLSX\'i XLSB\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLSX'ten XLSB'ye dönüştürmek karmaşık bir iş olabilir. Java SDK'mız, kaynak XLSX elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm XLSX'ten XLSB formatına dönüşümleri gerçekleştirir. Java kitaplığımız, XLSX'i çevrimiçi olarak XLSB dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, Java geliştiriciye güçlü işlevsellik kazandırır ve yüksek kaliteli XLSB çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Cells Bulut SDK\'yı kullanarak XLSX\'i XLSB\'ye dönüştürmek için Kod Örneği" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xlsx";
            String format = "xlsb";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xlsb";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer formatlara XLSX\'den XLSB\'ye dönüştürmek için Cells Cloud SDK for Java nasıl kullanılır?" >}}
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
