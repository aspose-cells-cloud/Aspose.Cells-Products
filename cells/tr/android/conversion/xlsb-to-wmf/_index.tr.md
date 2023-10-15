---
title:  Android'i kullanarak XLSB'yi WMF'ye dönüştürün
description:  XLSB biçimindeki bir dosyayı WMF biçimindeki bir dosyaya dönüştürmek için Android için Aspose.Cells Cloud SDK'yı kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSB\'yi WMF\'ye dönüştür" h2="XLSB\'yi WMF\'ye dönüştürmek için Android kitaplığı" p="Android projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, Android kullanarak XLSB\'yi WMF\'ye ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xlsb-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Android için Cells Cloud SDK\'yı kullanarak XLSB\'yi WMF\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLSB'den WMF'ye dönüştürmek karmaşık bir iş olabilir. Android SDK'mız, kaynak XLSB e-tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm XLSB'den WMF formatına dönüşümleri gerçekleştirir. Android kitaplığımız, XLSB'yi çevrimiçi olarak WMF dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, Android geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli WMF çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Cells Bulut SDK\'yı kullanarak XLSB\'yi WMF\'ye dönüştürmek için Android Kod Örneği" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xlsb";
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
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer formatlara XLSB\'den WMF\'ye dönüştürmek için Android için Cells Cloud SDK nasıl kullanılır?" >}}
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
