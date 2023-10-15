---
title:  Android'i kullanarak XLSM'yi BMP'e dönüştürün
description:  XLSM biçimindeki bir dosyayı BMP biçimindeki bir dosyaya dönüştürmek için Android için Aspose.Cells Cloud SDK'yı kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSM\'yi BMP\'e dönüştür" h2="XLSM\'yi BMP\'e dönüştürmek için Android kitaplığı" p="Android projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, Android kullanarak XLSM\'yi BMP\'e ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xlsm-to-bmp/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Android için Cells Cloud SDK\'yı kullanarak XLSM\'yi BMP\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLSM'den BMP'e dönüştürmek karmaşık bir iş olabilir. Android SDK'mız, kaynak XLSM elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm XLSM'den BMP formatına dönüşümleri gerçekleştirir. Android kitaplığımız, XLSM'yi çevrimiçi olarak BMP dosyalara dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, Android geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli BMP çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Cells Cloud SDK\'yı kullanarak XLSM\'yi BMP\'e dönüştürmek için Android Kod Örneği" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xlsm";
                String format = "bmp";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.bmp";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer XLSM formatlarından BMP\'e dönüştürmek için Android için Cells Cloud SDK nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `putConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Android 7 veya daha yenisi</li>
<li>Java(TM) SE Çalışma Zamanı Ortamı</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
